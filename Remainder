import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: appointments(),
    debugShowCheckedModeBanner: false,
  ));
}

class appointments extends StatefulWidget {
  @override
  _greenieappointments createState() => _greenieappointments();
}

class _greenieappointments extends State<appointments> {
  double deviceHeight(BuildContext context) =>
      MediaQuery.of(context).size.height;

  double deviceWidth(BuildContext context) => MediaQuery.of(context).size.width;
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Color(0xFFFFFFFF),
      appBar: AppBar(
        toolbarHeight: 90,
        backgroundColor: Color(0xFF0A0C35),
      ),
      body: ListView(
        // mainAxisAlignment: MainAxisAlignment.center,
        children: <Widget>[
          Container(
            height: deviceHeight(context) * 0.06,
            width: deviceWidth(context) * 0.5,
            //color: Colors.yellow,
            margin: EdgeInsets.only(
              left: deviceWidth(context) * 0.03,
              top: deviceHeight(context) * 0.02,
            ),
            child: Text(
              'Upcoming Meetings',
              textAlign: TextAlign.left,
              style: TextStyle(
                  fontWeight: FontWeight.w700,
                  color: Color(0xFF000000),
                  fontFamily: 'Comfortaa',
                  fontSize: 25),
            ),
          ),
          Container(
              height: deviceHeight(context) * 0.5,
              width: deviceWidth(context) * 0.5,
              child: SingleChildScrollView(
                child: Column(
                  children: <Widget>[
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 0,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.15, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFBAE7F8)),
                      child: Row(
                        children: [
                          Container(
                            height: 80,
                            width: 100,
                            // color: Colors.yellow,
                            margin: EdgeInsets.only(left: 0),
                            decoration: BoxDecoration(
                              border: Border.all(
                                  color: Color(0xFFFFFFFF), width: 1),
                              color: Colors.white,
                              shape: BoxShape.circle,
                            ),
                            child: IconButton(
                              icon: Icon(Icons.person),
                              padding: EdgeInsets.fromLTRB(0, 0, 0, 0),
                              color: Color(0xFFC4C4C4),
                              iconSize: 60,
                              onPressed: () {},
                            ),
                          ),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.0001,
                                    top: deviceHeight(context) * 0.02,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Name : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      '09:00 AM',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Friday , 4 Feb 2022',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF005544),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 17),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                  ],
                ),
              )),
          Container(
            height: deviceHeight(context) * 0.06,
            width: deviceWidth(context) * 0.5,
            //color: Colors.yellow,
            margin: EdgeInsets.only(
              left: deviceWidth(context) * 0.03,
              top: deviceHeight(context) * 0.03,
            ),
            child: Text(
              'Feedbacks to Answer',
              textAlign: TextAlign.left,
              style: TextStyle(
                  fontWeight: FontWeight.w700,
                  color: Color(0xFF000000),
                  fontFamily: 'Comfortaa',
                  fontSize: 25),
            ),
          ),
          Container(
              height: deviceHeight(context) * 0.2,
              width: deviceWidth(context) * 0.5,
              child: SingleChildScrollView(
                child: Column(
                  children: <Widget>[
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 0,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                    Container(
                      height: deviceHeight(context) * 0.16, //80
                      width: deviceWidth(context) * 1, //351
                      margin: EdgeInsets.only(
                        left: deviceWidth(context) * 0.03,
                        top: 10,
                        right: deviceWidth(context) * 0.03,
                      ),
                      decoration: BoxDecoration(
                          border:
                              Border.all(color: Color(0xFF000000), width: 1),
                          borderRadius: BorderRadius.circular(15),
                          color: Color(0xFFFFFFFF)),
                      child: Row(
                        children: [
                          Container(
                              height: 101,
                              width: 140,
                              // color: Colors.yellow,
                              margin: EdgeInsets.only(left: 0),
                              decoration: BoxDecoration(
                                border: Border.all(
                                    color: Color(0xFFFFFFFF), width: 1),
                                color: Colors.white,
                                shape: BoxShape.circle,
                              ),
                              child: Center(
                                child: Image(
                                    image: AssetImage('assets/greenie.jpeg')),
                              )),
                          Container(
                            child: Column(
                              mainAxisAlignment: MainAxisAlignment.center,
                              crossAxisAlignment: CrossAxisAlignment.start,
                              children: [
                                Container(
                                  height: deviceHeight(context) * 0.03,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.greenAccent,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                    top: deviceHeight(context) * 0.01,
                                  ),
                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Greenie Stage : XYZ',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                                Container(
                                  height: deviceHeight(context) * 0.04,
                                  width: deviceWidth(context) * 0.5,
                                  // color: Colors.yellow,
                                  margin: EdgeInsets.only(
                                    left: deviceWidth(context) * 0.05,
                                  ),

                                  child: Align(
                                    alignment: Alignment.centerLeft,
                                    child: Text(
                                      'Feedback :',
                                      textAlign: TextAlign.center,
                                      style: TextStyle(
                                          fontWeight: FontWeight.w400,
                                          color: Color(0xFF000000),
                                          fontFamily: 'Comfortaa',
                                          fontSize: 16),
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ],
                      ),
                    ),
                  ],
                ),
              )),
        ],
      ),
    );
  }
}
