# Entity Class

## Properties

## Methods

### **addEntityID**
`addEntityID(NBTTagCompound*)`

Adds the ID of this entity to the NBT given
### **addNotRiddenEntityID**
`addNotRiddenEntityID(NBTTagCompound*)`

Description not provided
### **addVelocity**
`addVelocity(Vector3*)`

Adds to the current velocity of the entity. Args: x, y, z
### **applyEntityCollision**
`applyEntityCollision(Entity*)`

Applies a velocity to each of the entities pushing them away from each other. Args: entity

### **copyDataFrom**
`copyDataFrom(Entity*, boolean)`

Description not provided
### **copyLocationAndAnglesFrom**
`copyLocationAndAnglesFrom(Entity*)`

Description not provided
### **dropItem**
`dropItem(number, number)`

Drops an item stack at the entity's position. Args: itemID, count
### **dropItemWithOffset**
`dropItemWithOffset(number, number, number)`

Drops an item stack with a specified y offset. Args: itemID, count, yOffset
### **entityDropItem**
`entityDropItem(ItemStackPtr, number)`

Drops an item at the position of the entity.
### **extinguish**
`extinguish()`

Removes fire from entity.
### **func_110123_P**
`func_110123_P()`

Description not provided
### **getAir**
`getAir()`

Description not provided
### **canBeCollidedWith**
`canBeCollidedWith()`

Returns true if other Entities should be prevented from moving through this Entity.
### **canBePushed**
`canBePushed()`

Returns true if this entity should push and be pushed by other entities when colliding.
### **canRenderOnFire**
`canRenderOnFire()`

Return whether this entity should be rendered as on fire.
### **doBlockCollisions**
`doBlockCollisions()`

Checks for block collisions, and calls the associated onBlockCollided method for the collided block.
### **doesEntityNotTriggerPressurePlate**
`doesEntityNotTriggerPressurePlate()`

Return whether this entity should NOT trigger a pressure plate or a tripwire.
### **getBottomPos**
`getBottomPos()`

Description not provided
### **getBoundingBox**
`getBoundingBox()`

Returns the bounding box for this entity
### **getBrightness**
`getBrightness(number)`

Gets how bright this entity is.
### **getBrightnessForRender**
`getBrightnessForRender(number)`

Description not provided
### **getCentorPos**
`getCentorPos()`

Description not provided
### **getCollisionBorderSize**
`getCollisionBorderSize()`

Description not provided
### **getCollisionBox**
`getCollisionBox(Entity*)`

Returns a boundingBox used to collide the entity with other entities and blocks. This enables the entity to be pushable on contact, like boats or minecarts.
### **getDistance**
`getDistance(Vector3)`

Gets the distance to the position. Args: x, y, z
### **getDistanceSq**
`getDistanceSq(Vector3)`

Gets the squared distance to the position. Args: x, y, z
### **getDistanceSqToEntity**
`getDistanceSqToEntity(Entity*)`

Returns the squared distance to the entity. Args: entity
### **getDistanceToEntity**
`getDistanceToEntity(Entity*)`

Returns the distance to the entity. Args: entity
### **getEntityName**
`getEntityName()`

Gets the username of the entity.
### **getExplosionResistance**
`getExplosionResistance(Explosion*, World*, BlockPos, Block*)`

Description not provided
### **getEyeHeight**
`getEyeHeight()`

Description not provided
### **getLastActiveItems**
`getLastActiveItems()`

Description not provided
### **getLookVec**
`getLookVec()`

Returns a (normalized) vector of where this entity is looking
### **
## Events 

### **attackEntityFrom**
`attackEntityFrom(DamageSource*, number)`

Called when the entity is attacked.

