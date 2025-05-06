```markdown
---
title: Dealing with platform connectivity issues
---

# Introduction

Every online store owner wants a seamless connection to platforms like Shopify. These connections ensure your store operates smoothly and that all your data syncs correctly. If you're having connectivity issues, follow this guide to troubleshoot and resolve them quickly.

# Ensure stable platform connections

Establishing a stable connection ensures your store's data flows without interruptions.

1. **Check network settings**: 
   - Make sure your internet connection is stable.
   - Restart your router if necessary. Sometimes a simple reset can solve connectivity issues.

:::tip
If you're using a wireless connection, try switching to a wired connection for better stability.
:::

2. **Turn off the firewall (if applicable)**: 
   - If you have a firewall enabled, temporarily disable it to check if it's blocking any essential connections.

:::caution
Remember to re-enable your firewall after testing to keep your network secure.
:::

3. **Grant file permissions (for managed hostings)**:
   - If you're using managed hosting, ensure that the `mp_connector/connector.php` file has both read and write access.

# Re-establish platform connections

Sometimes, the connection between your source platform and Shopify needs to be re-established.

1. **Reinstall the connector**:
   - Make sure your connector file is located at `your_store.com/mp_connector/connector.php`. Double-check this path.

2. **Update integration settings**:
   - Go to your Shopify settings and ensure all credentials and API permissions are accurate.
   - Re-enter any tokens or keys if prompted.

# Monitor connectivity stability

After reconnecting, it's important to keep an eye on the connectivity.

1. **Regularly check the connection**:
   - Periodically verify that data is syncing without issues.
   - If you notice delays, reassess the network settings and integration credentials.

2. **Use monitoring tools**:
   - Consider tools that provide real-time monitoring of your Shopify store's connectivity.

# Contact support

If you've followed the steps above and your issues persist, it's time to seek further assistance.

- Reach out to our support team with details of the problem. They're equipped to provide you with additional troubleshooting steps and solutions.

By following this guide, you'll solve most connectivity issues and ensure smooth operation for your online store. Keep these steps handy for any future connectivity hurdles!
```