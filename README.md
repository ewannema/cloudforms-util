# cloudforms-util

Aliases and environment settings to make working with CloudForms on the command line easier.

## To Build

    make rpm

## To install

Copy the rpm into the CloudForms VM and perform a normal RPM install.

## To Use

Shortcut aliases for CloudForms:

   cf    - bring up the rails console with $evm object loaded.
   
   auto  - tail -f automate.log
   
   evm   - tail -f evm.log
   
   log   - cd /var/www/miq/vmdb/log
   
   scrub - truncate the automate and evm logs.
