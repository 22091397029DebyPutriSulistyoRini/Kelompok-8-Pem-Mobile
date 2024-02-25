# Kelompok-8-Pem-Mobile

import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: const Text(
            'Kelompok 8',
            style: TextStyle(color: Colors.white),
          ),
          backgroundColor: Colors.blueAccent,
          centerTitle: true,
        ),
        body: Center(
          child: Image(
            image: AssetImage('image/Robot.png'),
          ),
        ),
        backgroundColor: Colors.white,
      ),
    ),
  );
}
