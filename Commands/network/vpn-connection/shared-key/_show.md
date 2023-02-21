# [Command] _network vpn-connection shared-key show_

Retrieve a VPN connection shared key.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2Nvbm5lY3Rpb25zL3t9L3NoYXJlZGtleQ==/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/connections/{}/sharedkey 2022-01-01 -->

#### examples

- View the shared key of a connection.
    ```bash
        network vpn-connection shared-key show -g MyResourceGroup --connection-name MyConnection
    ```

- Retrieve a VPN connection shared key.
    ```bash
        network vpn-connection shared-key show --connection-name MyConnection --resource-group MyResourceGroup --subscription MySubscription
    ```