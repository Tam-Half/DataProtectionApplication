velero login ...

velero backup-location get 

velero backup create "name of backup" \
--include-namespaces "namespace-to-backup" \
--storage-location "name-of-secondary-backup-location" 
