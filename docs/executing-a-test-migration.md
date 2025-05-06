```markdown
# Executing a test migration

When you're switching platforms, it's important to test the migration process to identify any potential errors before the final move. Running a test migration helps ensure that everything transfers smoothly. Let's go over how you can safely conduct a test migration with MigrationPro, identify possible errors, and verify its accuracy.

## Learning objectives

- Conduct a test migration safely.
- Identify potential migration errors.
- Verify test migration accuracy.

## Step-by-step guide

1. **Launch the MigrationPro app**  
   First, log in to your MigrationPro account using the [MigrationPro.io](https://app.migrationpro.io/auth/login) website.

2. **Select the test migration option**  
   Once logged in, click on "Create new migration." When prompted, choose the "Test migration" option instead of a full migration. This will simulate the migration and highlight any potential issues.

3. **Review test results**  
   After the test migration completes, you'll receive a report. Carefully review this to see how your data transferred.

4. **Note discrepancies**  
   Compare the results with your source store. Take note of any discrepancies or data that hasn't migrated as expected.

   :::caution
   If you notice duplicate entities, remember that running another migration without selecting the option to "Clear current data on target store" might cause this issue.
   :::

5. **Make necessary data adjustments**  
   If you spot any errors or data that needs correction, adjust your source store data or migration settings accordingly. Repeat the test migration if needed to verify your changes.

   :::tip
   Conduct a "Recent data migration" if there have been new additions to your store after a full migration, especially if you plan to deactivate the source store soon.
   :::

By following these steps, you'll ensure that your final migration to your Shopify store is successful. Happy migrating!
```