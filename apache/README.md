##apache Cookbook
===============
This Cookbook install simple apache server & configure virtual hosts according to site address



##Requirements
------------
This Cookbook requires Redhat,Centos,Fedora ( All RPM based OS)

#### packages
This Cookbook install Apache package i.e yum install httpd

##Attributes
----------

Below attributes created accordingly which creates virtual hosts

default["apache"]["sites"]["rups26032"] = { "port" => 80, "domain" => "rups26032.mylabserver.com" } 

default["apache"]["sites"]["rups26032b"] = { "port" => 80, "domain" => "rups26032b.mylabserver.com" }




#### apache::default

Apache virtual host document root will be create in /content/sites/domain_name


##License and Authors
-------------------
Authors: TODO: List authors
