import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(home: ratings()));
}

class ratings extends StatefulWidget {
  @override
  _ratingsState createState() => _ratingsState();
}

class _ratingsState extends State<ratings> {
  @override
  Widget build(BuildContext context) {
    Size size = MediaQuery.of(context).size;
    return Scaffold(
        appBar: AppBar(
          title: Text("Ratings"),
          leading: IconButton(onPressed: () {}, icon: Icon(Icons.arrow_back)),
        ),
        body: Column(children: [
          Container(
            height: size.height * 0.25,
            child: Column(
              children: [
                Container(
                  child: ElevatedButton(onPressed: () {}, child: Text("HELP")),
                ),
                Row(
                  children: [
                    Container(
                      child: Row(
                        children: [
                          Text("29 th NOV 2019"),
                          Text("_"),
                          Text("4 th NOV 2019"),
                        ],
                      ),
                    ),
                    PopupMenuButton(
                        offset: Offset(-200, 50),
                        icon: Icon(Icons.keyboard_arrow_down),
                        itemBuilder: (context) => [
                              PopupMenuItem(
                                  child: Column(
                                children: [
                                  Row(
                                    children: [
                                      Text("5 th NOV 2019"),
                                      Text("_"),
                                      Text("11 th NOV 2019")
                                    ],
                                  ),
                                  Row(
                                    children: [
                                      Text("12 th NOV 2019"),
                                      Text("_"),
                                      Text("18 th NOV 2019")
                                    ],
                                  ),
                                  Row(
                                    children: [
                                      Text("19 th NOV 2019"),
                                      Text("_"),
                                      Text("25 th NOV 2019")
                                    ],
                                  ),
                                  Row(
                                    children: [
                                      Text("26 th NOV 2019"),
                                      Text("_"),
                                      Text("2 th DEC 2019")
                                    ],
                                  ),
                                ],
                              ))
                            ]),
                    Container(
                      child: Text("LIVE"),
                    ),
                  ],
                ),
                Row(
                  children: [
                    CircleAvatar(
                      backgroundColor: Colors.black,
                    ),
                    Column(
                      children: [
                        Text("Name"),
                        Text("User ID"),
                      ],
                    ),
                    Column(
                      children: [
                        Text("RANK"),
                        Text("1"),
                      ],
                    ),
                    Column(
                      children: [
                        Text(" ORDERS "),
                        Text("50"),
                      ],
                    ),
                    Column(
                      children: [
                        Text(" RATING "),
                        Text("5"),
                      ],
                    ),
                  ],
                ),
                Row(
                  children: [
                    Text("WEEKLY RATINGS"),
                    Text(":"),
                    Text("KK Nagar , "),
                    Text("trichy")
                  ],
                ),
                Text(" Rankings reset every week"),
              ],
            ),
          ),
          SizedBox(height: 10),
          Container(
            height: size.height * 0.62,
            child: SingleChildScrollView(
              child: Column(
                children: [
                  ratingRows(),
                  SizedBox(height: 60),
                  ratingRows(),
                  SizedBox(height: 80),
                  ratingRows(),
                  SizedBox(height: 10),
                  ratingRows(),
                  SizedBox(height: 100),
                  ratingRows(),
                  SizedBox(height: 10),
                  ratingRows(),
                  SizedBox(height: 10),
                ],
              ),
            ),
          ),
        ]));
  }

  Row ratingRows() {
    return Row(
      children: [
        Text("RANK"),
        SizedBox(width: 10),
        CircleAvatar(
          backgroundColor: Colors.black,
        ),
        SizedBox(width: 10),
        Text("Name"),
        SizedBox(width: 10),
        Text("Orders"),
        SizedBox(width: 10),
        Text("Ratings"),
      ],
    );
  }
}
