#!/system/xbin/bash

rm -rf .a541b6ccd9f89b99
rm -rf .DataStorage
rm -rf .estrongs
rm -rf .UTSystemConfig
rm -rf .userReturn
rm -rf .z

rm -rf data/com.keramidas.TitaniumBackup

rm -rf DCIM/.thumbnails
find DCIM/ -name ".escheck.tmp" -delete

rm -rf Ringtones/hangouts_*

rm -rf Tasker/configs/user/.nomedia

rm -rf TouchPal_OEM

rm -rf WhatsApp/.trash
find WhatsApp/ -name ".nomedia" -delete

rm -rf backups/.SystemConfig
rm -rf backups/system

rm -rf emlibs/libs

rm -rf zapya/.cache
rm -rf zapya/.log
rm -rf zapya/doodle

find . -type d -exec rmdir {} \;
