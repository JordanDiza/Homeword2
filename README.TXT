Part IV
I will send the picture of the sun being blue and adding 2 suns

How to add 2 suns? Changed the sun1 color to blue by doing sun1.changeColor("blue");
Had to put private Circle sun2; after private Circle sun;
Had to add sun2.+ the method Ex. sun2.moveUp(); etc..

For the sunset I need to do this,
 } public void sunset() {
        sun.slowMoveVertical(300);
        sun.moveVertical(-300);
        drawn = true ;
    }

#19 I removed sun.slowMoveVertical and I added sun.moveVertivaly (10); like 8 times 

After a while of tring to find #20 I finally found it
so I needed to create 
private Person person; 
person = new Person ();
I needed to remove slowmove so that the sun stays down
public void person () {
        person.makeVisible();
        person.moveHorizontal (-100);
        person.slowMoveHorizontal (-100);
        
        drawn = true;
        
    }   
    