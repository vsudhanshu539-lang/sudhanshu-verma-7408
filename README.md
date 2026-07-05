# sudhanshu-verma-7408
import 'package:flutter/material.dart';

class HomePage extends StatelessWidget {
  const HomePage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text("Mobile Cleaner"),
      ),
      body: ListView(
        padding: const EdgeInsets.all(15),
        children: [

          Card(
            child: ListTile(
              leading: Icon(Icons.phone_android),
              title: Text("Device Details"),
              subtitle: Text("Brand, Model, Android Version"),
            ),
          ),

          Card(
            child: ListTile(
              leading: Icon(Icons.storage),
              title: Text("Storage"),
              subtitle: Text("Used / Free Storage"),
            ),
          ),

          Card(
            child: ListTile(
              leading: Icon(Icons.memory),
              title: Text("RAM"),
              subtitle: Text("Total & Free RAM"),
            ),
          ),

          Card(
            child: ListTile(
              leading: Icon(Icons.battery_full),
              title: Text("Battery"),
              subtitle: Text("Battery Percentage"),
            ),
          ),

          const SizedBox(height: 25),

          ElevatedButton.icon(
            icon: Icon(Icons.cleaning_services),
            label: Text("Clean Junk"),
            onPressed: () {

            },
          )

        ],
      ),
    );
  }
}ree RAM"),
            ),
          ),

          Card(
            child: ListTile(
              leading: Icon(Icons.battery_full),
              title: Text("Battery"),
              subtitle: Text("Battery Percentage"),
            ),
          ),

          const SizedBox(height: 25),

          ElevatedButton.icon(
            icon: Icon(Icons.cleaning_services),
            label: Text("Clean Junk"),
            onPressed: () {

            },
          )

        ],
      ),
    );
  }
}

