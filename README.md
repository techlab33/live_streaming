# live_4

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

    <application
        android:label="live_4"
        android:name="${applicationName}"
        android:usesCleartextTraffic="true"

        this line need for http support
        
        <h4>for ios</h4>
Open ios/Runner/Info.plist.
Add the following XML snippet within the <dict> section:

-------------------

        <key>NSAppTransportSecurity</key>
<p> <dict>
    <key>NSAllowsArbitraryLoads</key>
    <true/>
</dict> </p>

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
