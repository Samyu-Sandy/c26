# angryBirdsStage2.5
Angry Birds stage 2.5 with Class Inheritance and Images
class Log extends BaseClass{
  constructor(x,y,height,angle){
    super(x,y,20,height,angle);
    this.image = loadImage("sprites/wood2.png");
    Matter.Body.setAngle(this.body, angle);
  }
}