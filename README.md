# Bouncer

  This game is a block on the screen that moves aound and picks up speed depending on the elasticity. Its bounds are the edge   of the view.
  Used UIView to create a block from code on screen
  Created class BouncerBehavior which is a UIDynamicBehavior
  then used collider and gravity to keep the block in the views bounds, and for the block to fall. 
  created blockBehavior which told the block the elasticity, if it allowed rotation, the friction and resistance. 
  Used Core Motion, then used CMMotionManager to have the block accelorate.
  Created a settings bundle that could adjust the elasticity of the block. Used NSNotifications to be able to update the 
  elasticity in settings and not having to restart the app to adjust to new setting.
  
