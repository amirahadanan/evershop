# EverShop Setup Guide
Hello :) This document contains the steps required to setup this repository locally and connect to a hosted database in your machine.

## Pre-requisites
1. PostgreSQL (using the pgAdmin 4 system)

## Setting up the database locally
1. In pgAdmin 4, please create a new server with the following details:
	- name: postgres
	- host name/address: http://db.txjtbrvhjdngyyuskdtb.supabase.co
	- username: postgres
	- password: evershopadmin123#

## Installing the system
1. In the terminal, after cloning the repository and running `npm install`, please run the following command:
```npm run setup```
2. You will be prompted to fill in database details. Enter the following details: 
	- Postgres Database Host (localhost): db.fwplvygcgrdwrnwyogrm.supabase.co
	- Postgres Database Name:  postgres
	- Postgres Database User: postgres
	- PostgreSQL Database Password: evershopadmin123#

## If you have SETUP BEFORE THIS and DON'T WANT TO START FROM SCRATCH
1. Delete your .env file
2. Run `npm run setup`.

## Run development
Please run the `npm run dev` command.

## Build and start the system.
Please run the `npm run build` and `npm run start` command.

## Login as Admin Panel
- To access the admin panel, add `/admin` at the end of the browser URL.
- Login credentials:
  	- email: admin@admin.com
  	- password: evershopadmin123



