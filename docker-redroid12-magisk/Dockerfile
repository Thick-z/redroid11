from redroid11-magisk:v1.0

#ADD ./redroid11/ /
COPY  ./setup.sh / \
 ./magisk.tar /
ADD  ./sbin /
ADD  ./magisk /
ADD  ./busybox /data/adb/magisk/
ADD  ./remove.rc /vendor/etc/init
#Add ./system /
#RUN pm grant com.google.android.gms android.permission.ACCESS_COARSE_LOCATION && \
#    pm grant com.google.android.gms android.permission.ACCESS_FINE_LOCATION && \
#    pm grant com.google.android.setupwizard android.permission.READ_PHONE_STATE && \
#    pm grant com.google.android.setupwizard android.permission.READ_CONTACTS
