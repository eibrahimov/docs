```markdown
# Resolving data errors

Migrating your store's data to Shopify can sometimes lead to errors. These issues are normal and fixable. This guide will help you identify and resolve common data errors during migration. By the end, you'll learn to diagnose issues, apply solutions, and ensure a smooth data transition.

## Learning objectives

- Diagnose data issues
- Apply effective solutions

## Key steps

1. **Identify common error types**  
   Understand the common migration errors like missing data fields, duplication, and incorrect mappings. Identifying these early can save time.

2. **Use data troubleshooting tools**  
   Shopify provides tools to help diagnose migration errors. Check `Settings > Data migration` for tools that offer insights into potential issues.

3. **Implement recommended fixes**  
   - For missing data, make sure all fields are correctly mapped.
   - To resolve duplications, select the `Clear current data on target store` option before running the next migration.

   :::caution  
   Be careful when clearing data. Make sure you have backups to prevent the loss of important information.  
   :::

4. **Validate error resolution**  
   After applying fixes, run a test migration. Confirm all data appears accurately in your Shopify store. Use the `Start recent data migration` button to troubleshoot recent changes.

## Step-by-step instructions

1. **Run recent data migration**  
   - Go to your migration tool.
   - Click `Start recent data migration` to address any new data not included in the initial migration.

2. **Choose data to migrate**  
   - Go to `Settings > Data migration`.
   - Select the entities you need to transfer, like products and customers.

3. **Upload new CSV files**  
   - Click `Upload new CSV files` for any updated data.
   - Upload your files and click `Continue`.

4. **Implement full migration**  
   - Select `Start full migration` for a comprehensive data transfer.
   - Ensure no redundancy by selecting `Clear current data on target store`.

5. **Complete connection**  
   - Confirm by clicking `"Complete connection"` to finalize migration settings.

   :::tip  
   Always test your store after migration to ensure all data migrated correctly. Look for any inconsistencies that need addressing.  
   :::

For any unresolved issues, contact [support@migration.io](mailto:support@migration.io) for assistance. By following these steps, you'll not only resolve data errors effectively but also ensure your store runs smoothly on Shopify.
```