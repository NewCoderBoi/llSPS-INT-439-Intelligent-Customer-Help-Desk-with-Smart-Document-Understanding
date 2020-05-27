# llSPS-INT-439-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding
Intelligent Customer Help Desk with Smart Document Understanding

This project is based on an internship provided by SmartInternz (smartinternz.com).

# Project Overview

A chatbot, customer helpdesk, is designed for Ecobee3. Ecobee3 is a smart thermostat falling under the category of smart home devices. The chatbot helps the user to gather information by raising query. This chatbot accesses an unstructured document (user manual) of Ecobee3, by smart understanding of the document it replies to any query related to Ecobee3.

Here, we try to configure Watson Discovery to provide answers which are related to queries based on User manual.
Also, Watson Assistant is used to provide a proper dialogue flow for commmunication between a customer and the chatbot.
On raising product information involving queries, the Watson Assistant connects to Discovery Service using webhooks. 

# Purpose of Project

The main purpose is to enhance the efficiency of the chatbot (Customer Helpdesk) by incorporating Smart Document Understanding. So that, for both predefined and non-predefined queries answers are generated.  

# Video Link of project Explanation



# User Interface Link

https://node-red-nzfvk.eu-gb.mybluemix.net/ui/#!/0?socketid=eQO_mE3ruIxNDXuGAABV

# Contents in Repository

1. Cloud function action code (disco-action.js)
2. Watson Assistant Skill (skill-basic.json)
3. Node-RED flow (flows.json)
4. Code for function node in Node-RED flow (input_parsing_function_node.txt and parsing_function_node.txt)
5. Watson Discovery document (ecobee3_UserGuide)
6. Project report

