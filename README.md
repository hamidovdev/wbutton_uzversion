## Getting started

TODO: List prerequisites and provide or point to information on how to
start using the package.

### Example  
  
```dart  
import 'package:flutter/material.dart';
import 'package:wbutton_uzversion/widget/w_button.dart';

void main() {
  runApp(const MainApp());
}

class MainApp extends StatelessWidget {
  const MainApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        body: Center(
          child: WButton(
            onTap: () {},
            text: "Submit",
            borderRadius: 10,
            textStyle: const TextStyle(
              fontSize: 22,
              color: Colors.white,
              fontWeight: FontWeight.w500,
            ),
            // disabled: false,
            // loading: false,
          ),
        ),
      ),
    );
  }
}
  
```