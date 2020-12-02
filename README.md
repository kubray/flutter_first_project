# flutter_first_project
My first flutter experience
void main() {
  runApp(MyFirstApp()

  );
}

class MyFirstApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme:ThemeData.dark(),
      home: Scaffold(

        appBar: AppBar(

          title:Center(
            child :Text(
              'My Contact Information',
textAlign: TextAlign.center,
          style : TextStyle(
            color: Colors.red,
            fontSize: 19,



          ),
        ),
          ),
        ),
        body: Column(

          crossAxisAlignment: CrossAxisAlignment.stretch,

          children: [
            Padding(
              padding: const EdgeInsets.all(30),
              child: CircleAvatar(
                radius:100,
                backgroundImage : AssetImage('image/kubra4.jpg'),

                ),
              ),
            Divider(
              height: 73,
              thickness:2,
            ),
            Row(
              children: [
                Container(


                  child:Padding(

                  padding: const EdgeInsets.only(left:50 ,bottom:10),
                    child: Text (
                    'NAME',
                    style: TextStyle(
                      color :Colors.white,
                      fontSize: 15,
                    ),
                  ),
                ),
                ),
              ],
            ),
            Row(
              children: [
                Container(


                  child:Padding(

                    padding: const EdgeInsets.only(left:50.0,bottom:30.0),
                    child: Text (
                      'Kübra Ay',
                      style: TextStyle(
                        color :Colors.red,
                        fontSize: 22,
                        fontFamily:'NerkoOne',

                      ),
                    ),
                  ),
                ),
              ],
            ),
            Row(
              children: [
                Container(



                  padding :EdgeInsets.only(left:50.0,bottom:32.0),
                  child:Icon(

                    Icons.phone_callback,
                    color: Colors.white,
                    size: 20,
                  ),
                ),
                Padding(
                  padding: const EdgeInsets.only(left:10.0,bottom:32.0),
                  child: Text (

                    'O(545) 663 13 50',
                    style: TextStyle(
                      color :Colors.white,
                      fontSize: 15,
                    ),
                  ),
                ),
              ],
            ),


            Row(
              children: [
                Container(


                  padding :EdgeInsets.only(left:50.0,bottom:31),
                  child:Icon(

                    Icons.mail,
                    color: Colors.white,
                    size: 20,
                  ),
                ),
                Padding(
                  padding: const EdgeInsets.only(left:10.0,bottom:31),
                  child: Text (

                    'kubra@gmail.com',
                    style: TextStyle(
                      color :Colors.white,
                      fontSize: 15,
                    ),
                  ),
                ),
              ],
            ),
            Row(
              children: [
                Container(


                  padding :EdgeInsets.only(left:50.0,bottom:30),
                  child:Icon(

                    Icons.print,
                    color: Colors.white,
                    size: 20,
                  ),
                ),
                Padding(
                  padding: const EdgeInsets.only(left:10.0,bottom:31),
                  child: Text (

                    'O(212) 667 86 97',
                    style: TextStyle(
                      color :Colors.white,
                      fontSize: 15,
                    ),
                  ),
                ),
              ],
            ),






          ],
        ),
      ),

    );
  }
}
