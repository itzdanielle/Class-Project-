# Class-Project-
#include <iostream>
#include <string>
using namespace std;

void printDescription () {
  cout << "Hi Explorer, Welcome to the Amazon!" << endl;
}
int optionRuinsWildlife (int& answer) {
  cout << "You are now approaching the entrance to the Amazon. There is going to be two groups that will split up depending on what you want to see. Please select one of the follwoing..." << endl;
  cout << "1 - Ancient Ruins of the Amazon" << endl
  << "2 - for the Wildlife of the Amazon" << endl;
  cin >> answer;
  return answer;
}
int optionPrymaidRemains ( int& answer ) {
    cout << "Excellent choice! Here at the Ancient Ruins of the Amazon there is tons of history. We have so much to explore. Ahead they're pryamids that we can see in the distance however, there are also really famous ancient remains to be seeen. We do not have time to do both please choose the follwoing..." << endl;
    cout << "1 - Pryamid"<< endl 
    << "2 - Ancient Remains" << endl;
    cin >> answer;
    return answer;
}
int optionPryamids (int& answer){
    cout << "Great choice! The pryamids here are very old and are the most stunning in the world. Today we get to walk to the top and see some of the best views of the Amazon. When we get to the top there's more to see. Please select one of the following... " << endl;
    cout << "1 - Go inside the Pryamid " << endl
    << "2 - Take a photo with the old ruler's statue" << endl;
    cin >> answer;
    return answer;
}
int optionInsidePryamid (int& answer) {
    cout << " Fanstastic choice! Inside the pryamid you can see very beautiful art along the floor and ceiling. The people of this time were very skilled and spent a lot of time making there city as beautiful as can be. The tour guide is calling us to come back towards the entrance, there is another one of kind opportunity to see the Amazon. Please choose one of the following options..." << endl;
    cout << "1 - Hot air balloon ride" << endl
    << "2 - Stay on the ground" << endl;
    cin >> answer;
    return answer;
}

int optionHotAirBalloonRide (int& answer) {
  cout << "You have a great sense of adventure! Now that you are on the hot air ballon and overlooking the amazon, you can see that there is nothing but green lush trees and you hear waterfalls and birds. We can go toward the waterfalls or keeping looking over the trees to see more creatures that live only in the branches. Please select one of the following..." << endl;
  cout << "1 - Float toward the waterfalls" << endl
  << "2 - Keep on look at the nature in the trees " << endl;
  cin >> answer;
  return answer;
}
int optionFloatToWaterFalls (int& answer){
  cout << "Amazing choice. We came at the perfect time to see the rainbow just over the three waterfalls. As we float over the huge waterfall, down below you can see the elephants have just arrived to take a bath. Unfortunately we have come close to the end of our tour of the amazon. Please choose one of the following on how you would like to go back..." << endl;
  cout << "1 - By hot air balloon " << endl 
  << "2 - land near here and go back by jeep (longer way)" << endl;
  cin >> answer;
  return answer;
}
void optionByAirBalloon () {
  cout << "The view above the Amazon is nothing like anywhere else and I hope you enjoyed your adventure of the Amazon!" << endl;
}
void optionLandAndJeep () {
  cout << "The Amazon is so unique since there's always something to see in every direction. I hope you enjoyed your adventure of the Amazon and come back soon!" << endl;
}
int optionKeepLookingAtNature (int& answer) {
  cout << "I like your sense of admiring nature. We can head down a little to get a better look at just what type of creatures live here. We can see many types of birds flying around and even some monkeys are peaking their heads at the top of the trees. It is sadly near the end of our tour of the Amazon. Which way back would you prefer? Select one of the following..." << endl;
  cout << "1 - Go a little further to see the waterfalls and headback" << endl
  << "2 - Go back now to get some good pictures of the sunset" << endl;
  cin >> answer;
  return answer;
}
void optionGoFurther () {
  cout << "I hope you enjoyed the waterfalls and unfortunately the tour is over. I hope you enjoyed your adventure of the Amazon and come back soon!" << endl;
}
void optionGetSomePictures () {
  cout << "The views from the hot air balloon are like none other and good idea to take those photos before we land back down soon. Our tour has come to an end and I hope you enjoyed exploring the Amazon!" << endl;
}
int optionStayOnGround (int& answer) {
  cout << "It's okay to get nervous to fly on a hot air ballon, there's still plenty to do on the ground of the amazon. We are going to head back down the pyramid now so we can explore more. Please choose one of the following to do as we near the end of our tour of the amazon..." << endl;
  cout << "1 - Last minute jeep ride through the amazon" << endl
  << "2 - Look at the old statues near the entrance of the city" << endl;
  cin >> answer;
  return answer;
}
int optionLookAtStatues (int& answer) {
  cout << "The statues are really incredible, they are over 12 feet high and the craftsmanship is amazing. This one is of a warrior and you can see the detail the closer you get. Our tour is coming to an end we have a few options on what to do last. Please choose one of the following... " << endl;
  cout << "1 - Take a photo with the statue" << endl
  << "2 - Take a photo with the prymaid in the background" << endl;
  cin >> answer;
  return answer;
}
void optionPhotoWithStatue () {
  cout << "Awesome photo! I am sad to say that this is where the tour ends. I hope you enjoyed exploring the Amazon and come back soon!" << endl;
}
void optionPhotoWithPryamid () {
  cout << "Awesome photo! I am sad to say that this is where the tour ends. I hope you enjoyed exploring the Amazon and come back soon!" << endl;
}
int optionLastMinJeepRide (int& answer) {
  cout << "You made a good choice. We are taking a last minute look around the Amazon where we can see a lot of animals. Over to your right you may see a panther hiding behind a tree looking for something to eat and to your left you might also see a small monkey picking at some berries. It is really cool to see animals this close. We should be turning back we might take a couple ways, which one would you like?" << endl;
  cout << "1 - Scenic route " << endl
  << "2 - quickest way to back so we can eat" << endl;
  cin >> answer;
  return answer;
}
void optionScenicRoute () {
  cout << "Seeing the Amazon for a little longer is definitely the right choice. I hope you had an amazing adventure and come back soon!" << endl;
}
void optionQuickWayBack () {
  cout << "You had a long day and deserve a nice meal. I hope you had a fantastic adventure exploring the Amazon and come back soon!" << endl;
}
int optionTakeAPhoto (int& answer) {
    cout << "Great choice! The statue is one of the best things to see since there's nothing else like it here in the Amazon. The tour guide says that they are offering a unique opportunity to see the Amazon on an elephant's back. Would you like to go? Please choose one of the following..." << endl;
    cout << "1 - Go on elephant ride" << endl
    << "2 - Feed the elephants" << endl;
    cin >> answer;
    return answer;
}
int optionFeedAllElephants (int& answer) {  
  cout << "Luckily here in the Amazon the elephants food is all around us. They however love human food when they get the chance but you can choose what you want to feed it. Select which one you would like to feed the elephant" << endl;
  cout << "1 - peanuts" << endl
  << "2 - bananas" << endl;
  cin >> answer;
  return answer;
}
int optionFeedElephantPeanuts (int& answer) { 
  cout << "The elephant really enjoyed the peanuts, a few more came closer to get some as well. They seem to be wanting a snack that is in your bag, you could distract them with more peanuts or give them your snack. Which do you choose? " << endl;
  cout << "1 - give them your snack" << endl
  << "2 - distract them with more peanuts" << endl;
  cin >> answer;
  return answer;
}
void optionGiveThemYourSnack () {
  cout << "They ate your snack really fast, they seem to really like you. They are leaving now to go find more food elsewhere and it is also time for us to end the tour. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
void optionGiveMorePeanuts () {
  cout << "They ate the rest of the peanuts really fast, they seem to really like you. They are leaving now to go find more food elsewhere and it is also time for us to end the tour. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
int optionFeedElephantsBananas (int& answer) { 
cout << "The elephants enjoyed the bananas you gave them and are wanting more. A few more elephants are coming over to also get some food and a few of them want the snack in your bag. What do want to do?" << endl;
cout << "1 - distract them with more bananas" << endl
<< "2 - give them your snack" << endl;
cin >> answer;
return answer;
}
void optionDistractThemWithBananas () {
  cout << "The elephants really enjoyed the bananas since they did not have to go looking for them. They are getting ready to leave and it is time for our tour group to head back. The tour has officially ended and I hope you enjoyed exploring the Amazon." << endl;
}
void optionGiveThemYourSnackNotABanana () {
  cout << "The elephant really enjoyed your snack! It is time to head back and sadly end the tour of the Amazon. I hope you enjoyed exploring the Amazon and come back soon!" << endl;
}
int optionElephantRide (int& answer) {
  cout << "Elephants love humans but we must be careful. Although we wanted to ride the elephants we cannot do so if they don't wish. It appears that these elephants just want to play in the water. Please select one of the following to do..." << endl;
  cout << "1 - Play with the elephants in the water " << endl
  << "2 - Feed the elephants some food" << endl;
  cin >> answer;
  return answer;
}

int optionPlayWithElephants (int& answer) {  
  cout << "I hope you do not mind being soaked by the elephants that just sprayed you but everyone could use a cooling off. It looks like one of the smaller elephants wants to play a little closer. It appears that it was just smelling the food in your backpack. Which would you rather do?" << endl;
  cout << "1 - give the elephant some of your snack" << endl
  << "2 - Distract the elephant with some peanuts" << endl;
  cin >> answer;
  return answer;
}
void optionGiveElephantSnack () { 
  cout << "The elephant really enjoyed your snack! It is time to head back and sadly end the tour of the Amazon. I hope you enjoyed exploring the Amazon and come back soon!" << endl;
}
void optionDistractWithPeanuts () { 
  cout << "The elephants really enjoyed the peanuts since they cannot have them often. They are getting ready to leave and it is time for our tour group to head back. The tour has officially ended and I hope you enjoyed exploring the Amazon." << endl;
}
int optionFeedElephants (int& answer) { 
  cout << "Luckily here in the Amazon the elephants food is all around us. They however lokve human food when they get the chance but you can choose what you want to feed it. Select which one you would like to feed the elephant" << endl;
  cout << "1 - peanuts" << endl
  << "2 - bananas" << endl;
  cin >> answer;
  return answer;
}
void optionFeedPeanuts () {
  cout << "The elephant really enjoyed the peanuts and seems like they are leaving to find more food. It is also time for us to end the tour and I hope you enjoyed exploring the Amazon, come back soon!" << endl;
}
void optionFeedBananas () {
  cout << "The elephant really enjoyed the bananas and seems like they are leaving to find more food. It is also time for us to end the tour and I hope you enjoyed exploring the Amazon, come back soon!" << endl;
}
int optionReamins (int& answer) {
    cout << "Great choice! The ancient remains here date back thousands of years and are preserved very well. There is more than meets the eye, there are even more in a cave a little down away near a waterfall where you can swim. Please choose one of the following..." << endl;
    cout << "1 - remains in the cave" << endl
    << "2 - jump in the water " << endl;
    cin >> answer;
    return answer;
}

int optionRemainsCave (int& answer) {  
    cout << "Nice choice! In the cave the remains are very nicely preserved and if you look on the wall of the cave... the art work are stories told about their lives. There very talented artist and if you turn around there is something shiny. It looks like crystals, please choose one of the following..." << endl;
    cout << "1 - Go look at the crystals" << endl
    << "2 - Go back outside the cave" << endl;
    cin >> answer;
    return answer;
}
int optionLookAtCrystals (int& answer) { 
  cout << "You can see the crystals are small but they are burried under some rock which can be easily removed with some tools. You have to be very careful to not damage the crystal but if you'd like to go look at the other parts of the cave before going back out you can as well. Please choose one of the following..." << endl;
  cout << "1 - Dig for some crystals" << endl
  << "2 - Look around the cave some more" << endl;
  cin >> answer;
  return answer;
}
int optionDigForCrystals (int& answer ) {
  cout << "You are getting close to a medium size crystal but you are also close to hitting it and possibly damaging it. There is one other near by that seems easier to get but you will have less time to get it since we are leaving soon. You can choose what you would rather do " << endl;
  cout << "1 - keep going on the crystal you started with" << endl
  << "2 - start on the easier crystal with less time" << endl;
  cin >> answer;
  return answer;
}
void optionKeepGoingOnCrystal () {
  cout << "Nice choice, the crystal came out perfectly and just in time for us to be heading back. I hope you enjoyed you tour of the amazon and come back soon!" << endl;
}
void optionStartOnNewCrystal () {
  cout << "Nice! You just got the crystal in time for us to be heading back. It appears to be a rare one and luckily you choose that one. This is where our tour ends of the amazon and I hope you enjoyed exploring and come back soon!" << endl;
}
int optionGoingBackOutsideCave (int& answer) { 
  cout << "There is a lot more exciting things to look around here than in the cave. The waterfall next to it goes right down to the river. We can go down to the river or we can head back to the jeep for a last ride through the amazon. Please choose one of the following... " << endl;
  cout << "1 - go down to the river" << endl
  << "2 - go back to the jeep for a last ride " << endl;
  cin >> answer;
  return answer;
}
void optionGoToRiver () {
cout << "The river as crystal clear water and you can see all the fish swimming around. If you look down the river you can see all the animals drinking from it. Unfortunately we have to head back and end the tour of the amazon. I hope you enjoyed exploring and come back soon!" << endl;
}
void optionGoBackForLastJeepRide () {
  cout << "Great choice! As we are heading back to the entrance of the amazon there is many creatures on the way back. If you look to your left you can see some of the many species of monkeys haning from the trees and everywhere else is filled with thousands of birds and other creatures. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
int optionJumpInWater (int& answer) { 
    cout << "Nice! It was a hot day and jumping in the water was a great way to cool off. If you look up, the trees cover the water so it doesn't evaporate. If you looks closely enough to the trees, you can see some colorful beaks of birds. They're many here in the Amazon. Please choose one of the following on what you want to do next..." << endl;
    cout << "1 - climb the rocks to see the birds better" << endl
    << "2 - take another jump in the water" << endl;
    cin >> answer;
    return answer;
}
int optionClimbRocks (int& answer) { 
  cout << "You did an excellent job climbing the rocks since they're very slippery from the water. The view of the birds is much better higher up and thankfully our tour guide has some sugar water to feed them but you have to stay very still. If that doesn't sound very fun we are able to jump off this ledge into the water and don't worry we aren't very high up. Please choose one of the following to do..." << endl;
  cout << "1 - Feed the birds" << endl 
  << "2 - jump of the ledge into the water" << endl;
  cin >> answer;
  return answer;
}
int optionFeedBirds (int& answer) { 
  cout << "Wow it looks like there's is a parrot coming your way. You have to be very still and make sure that you don't make a lot of movements. After they ate all of the sugar water we can climb the rocks a bit more to get a nice view of the amazon before we head back or we can go back now. Please choose one of the following..." << endl;
  cout << "1 - climb a little more for a nice view of the amazon" << endl
  << "2 - go back now" << endl;
  cin >> answer;
  return answer;
}
void optionClimbALittleMore () {
  cout << "I like your sense of adventure. The view of the sunset peaking through all of the trees is incredible and nothing like anywhere else on earth. This sadly concludes our tour of the amazon and I hope you enjoyed exploring." << endl;
}
void optionGoBackNow () {
  cout << "I am sad to say by going back we have officially ended to tour of the amazon. I hope you enjoyed your time exploring the different parts of the amazon and come back soon!" << endl;
}
int optionJumpOffLedgeIntoWater (int& answer) { 
cout << "Wow I like your sense of adventure, now that you are cooled off we have just a few minute last things to do. You are allowed to take a rock from the river to keep with you or you can take this flower and plant the seeds wherever you wish later on. Please choose one of the following..." << endl;
cout << "1 - take a rock " << endl
<< "2 - take a flower to plant" << endl;
cin >> answer;
return answer;
}
void optionTakeARock (){
  cout << "That is a great choice and if you look closely there is some unique colors underneath if you scrub it a little. Now you have a memnto from your tour exploring the amazon. I hope you had a fun time exploring the amazon and come back soon!" << endl;
}
void optionTakeFlower () {
  cout << "That is a great choice to also plant more beautiful flowers. They are unique to the amazon so make sure if you plant it, that is has a similar environment to the amazon. I hope you enjoyed your tour of the amazon and come back soon!" << endl;
}
int optionTakeAnotherJumpInWater (int& answer) { 
  cout << "Now that you are cooled off there are some elephants coming this way. They seem the be thirsty and we should give them some space. The little elephants seem to like to play in the water. We also have some food on the jeep to feed them if we came across the elephants, what should we feed them?" << endl;
  cout << "1 - Bananas" << endl
  << "2 - mangos" << endl;
  cin >> answer;
  return answer;
}
int optionGiveBananas (int& answer) { 
cout << "The elephants love bananas, they usually have to wait till they fall from the trees because they grow so high up. We can give them more or leave what we have on the edge of the water so they can all eat them. What would you like to do?" << endl;
cout << "1 - give the elephants more bananas" << endl
<< "2 - leave the rest on the ground" << endl;
cin >> answer;
return answer;
}
void optionLeaveBananas () {
  cout << "The elephants are so happy to be getting a lot of food. They seem to be leavaing now and it is time for us to head back to the entrance. I hope you enjoyed your tour of the amazon and come back soon!" << endl;
}
void optionLeaveRestOfBananas () {
  cout << "The elephants are now all eating and enjoying their bananas. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
int optionGiveMangos (int& answer) { 
cout << "The elephants love mangos, they usually have to wait till they fall from the trees because they grow so high up. We can give them more or leave what we have on the edge of the water so they can all eat them. What would you like to do?" << endl;
cout << "1 - give the elephants more mangos" << endl
<< "2 - leave the rest on the ground" << endl;
cin >> answer;
return answer;
}
void optionLeaveMangos () {
  cout << "The elephants are so happy to be getting a lot of food. They seem to be leavaing now and it is time for us to head back to the entrance. I hope you enjoyed your tour of the amazon and come back soon!" << endl;
}
void optionLeaveRestOfMangos() {
  cout << "The elephants are now all eating and enjoying their mangos. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
int optionTigersSnakes (int& answer) {
  cout << "Great choice! The wildlife here in the Amazon is nothing like any other place in the world. There is so much to see and explore (with safety precautions of course), where would you like to start? Please select one of the following..." << endl;
  cout << "1 - tigers " << endl
  << "2 - snakes " << endl;
  cin >> answer;
  return answer;
}
int optionTigers (int& answer) { 
    cout << "Nice choice! Tigers here in the Amazon are one of the top predators and you would not want to be its next meal. They are beautiful creatures to watch but you must always be careful. There seems to be two insight but not going in the same direction. Which one would you like to follow, please choose one of the following... " << endl;
    cout << "1 - tiger going back to its cubs" << endl
    << "2 - the tiger that is approacing the jeep" << endl;
    cin >> answer;
    return answer;
}
int optionFollowTigerToCubs (int& answer) { 
cout << "We are being sure to keep our distance and still be able to see tigers in their natural habitat. However, it is getting harder to follow this tiger since they keep their cubs hidden for protect. We can see some animals in the distance should we go see what it is?" << endl;
cout << "1 - yes, go see what animal it is" << endl
<< "2 - no, keep riding till we see something else" << endl;
cin >> answer;
return answer;
}
int optionGoSeeAnimals (int& answer) { 
  cout << "As we are getting closer we can see that they are gorillas. They are always with their clan and are never alone. It seems to be that they are eating bananas which is their favorite kind of food. Should we watch them a little bit more or feed them more bananas that we have?" << endl;
  cout << "1 - watch them eat" << endl
  << "2 - feed them some more bananas" << endl;
  cin >> answer;
  return answer;
}
int optionWatchThemEat (int& answer) { 
cout << "It's better to keep the distance and let them enjoy their food. You can take a photo of them but you cannot use flash but if you are ready to leave we can head back soon." << endl;
cout << "1 - take a photo of the gorillas" << endl
<< "2 - head back now" << endl;
cin >> answer;
return answer;
}
void optionTakePhotoOfGorillas () {
  cout << "That was a great photo you took and now you can keep it for memories of your tour. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
void optionGoBackRn () {
  cout << "It has been a long day and you have seen so many amazing things of the amazon. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
int optionFeedGorillasMoreBananas (int& answer) { 
cout << "The gorillas love bananas, they usually have to wait till they fall from the trees because they grow so high up or climb themselves. We can give them more or leave what we have on the edge of the where they are eating. What would you like to do?" << endl;
cout << "1 - give the gorillas more banans" << endl
<< "2 - leave the rest on the ground" << endl;
cin >> answer;
return answer;
}
void optionGiveGorillasMoreBananas () {
cout << "The gorillas are so happy to be getting a lot of food. They seem to be leavaing now to sleep and it is time for us to head back to the entrance. I hope you enjoyed your tour of the amazon and come back soon!" << endl;
}
void optionLeaveGorillasBananas () {
cout << "The gorillas are now all eating and enjoying their bananas. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
int optionTigerApproachingJeep (int& answer) { 
  cout << "The tiger approaching the jeep seems to not be so interested in us but another tiger that was behind us. We are about to move out of the way so we let nature take its course. We can see some very largenother creatures in the distance, they are elephants. They are heading toward a water source and should we watch them or get closer?" << endl;
  cout << "1 - watch them only" << endl
  << "2 - get closer" << endl;
  cin >> answer;
  return answer;
}
int optionWatchElephantsOnly (int& answer) { 
cout << "Good choice to only watch them. We are able to see that there are a lot of adult elephants and a couple young elephants. The young elephants seem to want to play in the water, we could take a photo of the elephants with no flash or get out of the jeep at distance to see better." << endl;
cout << "1 - take a photo" << endl
<< "2 - get out of jeep from a distance" << endl;
cin >> answer; 
return answer;
}
int optionTakePhotoOfElephants (int& answer) {  
  cout << "Nice photo that you have there. You were able to capture the little elephant spraying another little elephant with it's trunk. Would you like to take another photo or watch a little more and go back?" << endl;
  cout << "1 - take another photo of the little elephants" << endl
  << "2 - go back soon" << endl;
  cin >> answer;
  return answer;
}
void optionTakeOneLastPhotoOfElephant () {
  cout << "I am glad you were able to take all the photos you wanted. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
void optionWatchAndGoBack () {
  cout << "I hope you enjoyed watching the elephants take baths and play in the water. It is time to end the tour of the amazon and I hope you had a fun time exploring!" << endl;
}
int optionGetOutOfJeepDistance (int& answer) { 
cout << "You can see the elephants much better now but make sure they do not see you otherwise they will come. You can take a closer photo or stay here and just watch them. Please choose which one you would like to do..." << endl;
cout << "1 - take a closer photo" << endl
<< "2 - watch the elephants" << endl;
cin >> answer;
return answer;
}
void optionTakeACloserPhoto () {
  cout << "I am glad you were able to take all the photos you wanted. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
} 
void optionWatchElephantsPlay () {
cout << "I hope you enjoyed watching the elephants take baths and play in the water. It is time to end the tour of the amazon and I hope you had a fun time exploring!" << endl;
}
int optionGetCloserToElephants (int& answer) { 
cout << "The elephants are happily eating some berries and fruits. We happen to have some on the jeep. Should we feed the elephants or should we just watch them?" << endl;
cout << "1 - feed the elephants" << endl
<< "2 - watch them only" << endl;
cin >> answer;
return answer;
}
int optionWhatToFeedElephants (int& answer) { 
cout << "Good choice. What should we feed them we have some different types on the jeep that we could give them." << endl;
cout << "1 - mangos" << endl
<< "2 - watermelon" << endl;
cin >> answer;
return answer;
}
void optionFeedElephantsTheMangos () {
cout << "The elephants are now all eating and enjoying their mangos. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
void optionFeedElephantsTheWatermelon (){
cout << "The elephants are now all eating and enjoying their watermelon. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
int optionWatchElephantsOnlyThere (int& answer) { 
cout << "You can see the elephants much better now but make sure they do not see you otherwise they will come. You can take a closer photo or stay here and just watch them. Please choose which one you would like to do..." << endl;
cout << "1 - take a closer photo" << endl
<< "2 - watch the elephants" << endl;
cin >> answer;
return answer;
}
void optionTakeAPhotoBetterOfElephants () {
cout << "I am glad you were able to take all the photos you wanted of the elephants. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
void optionElephantWatching () {
  cout << "I hope you enjoyed watching the elephants eat. It is time to end the tour of the amazon and I hope you had a fun time exploring!" << endl;
}
int optionSnakes (int& answer) { // this is 3 
cout << "Nice choice. Snakes have lived in this part of the world for millions of years and they have many different kinds. They can grow up to 20ft in length and are sometimes brightly colored. The snake ahead seems to be hidden since its camouflage is impeccable. Next to it are some unique colorful frogs and birds. There are thousands of each in the Amazon, we can see more if we look hard enough..." << endl;
cout << "1 - go to the river for the river snakes " << endl
<< "2 - stay in the amazon for those that are in the trees " << endl;
cin >> answer;
return answer;
}
int optionRiverSnakes (int& answer) { // this is 4 
  cout << "Good choice. River snakes can eat their food in the water and on land. They are great swimmers and they swim really fast so they are hard to see. We can wait here for a moment to see if we can sight one or when can ride along the river to see what else we can come across" << endl;
  cout << "1 - wait to see if we can sight one" << endl
  << "2 - ride along the river" << endl;
  cin >> answer;
  return answer;
}
int optionWaitToSeeARiverSnake (int& answer) { // this is 5 
  cout << "As we are waiting we can see other creatures in the water like fish and frogs. If you are luckly enough you can snap a photo of it. However, keep your distance since they can be poisonous." << endl;
  cout << "1 - wait a little longer to see a river snake" << endl
  << "2 - take a photo of the other creatures in the river"  << endl;
  cin >> answer;
  return answer;
}
int optionWaitALittleLonger (int& answer) { // this is 6 
cout << "It looks like there's not really any river snakes in this area but you can take a rock from the river to save or a near by flower to plant somewhere else. Which would you like to do?" << endl;
cout << "1 - take a rock " << endl
<< "2 - take a flower to plant" << endl;
cin >> answer;
return answer;
}
void optionTakeARockFromRiver (){
  cout << "That is a great choice and if you look closely there is some unique colors underneath if you scrub it a little. Now you have a memnto from your tour exploring the amazon. I hope you had a fun time exploring the amazon and come back soon!" << endl;
}
void optionTakeFlowerByRiver () {
  cout << "That is a great choice to also plant more beautiful flowers. They are unique to the amazon so make sure if you plant it, that is has a similar environment to the amazon. I hope you enjoyed your tour of the amazon and come back soon!" << endl;
}
int optionTakeAPhotoOfOtherCreatures (int& answer) { // this is 6
cout << "There are so many other creatures that we have seen on the river. There are many frogs and birds that are constantly making their unique calls. Which creature is your favorite? " << endl;
cout << "1 - frogs" << endl
<< "2 - birds" << endl;
cin >> answer;
return answer;
}
void optionFavAnimalFrog () {
  cout << "That is a really cool animal. There are thousands here in the amazon and all are different colors. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
void optionFavAnimalBird () {
  cout << "That is really cool animal. There are thousands here in the amazon and all are different colors. I hope you enjoyed exploring the amazon and come back soon!" << endl;
}
int optionRideAlongRiver (int& answer) { // this is 5 
cout << "The river is one of the main reasons that there is so much life in the amazon. A little down we can see some gorillas drinking water. What would you like to do?" << endl;
cout << "1 - get a little closer" << endl
<< "2 - keep a distance" << endl;
cin >> answer;
return answer;
}
int optionGetCloserOnRiver (int& answer) { // this is 6
  cout << "Great choice. We are still a little far away but it is the best time to take a photo. If not you can always just watch them be in their natural habitat. Which would you like to do?" << endl;
  cout << "1 - take a photo" << endl
  << "2 - just watch from a distance" << endl;
  cin >> answer;
  return answer;
}
void optionWatchFromDistOnRiver (){
cout << "The gorillas are now all drinking water and enjoying their bath. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
void optionTakePhotoFromDistOnRiver () {
cout << "I am glad you were able to take all the photos you wanted of the gorillas. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
int optionKeepDistOnRiver (int& answer ) { // this is 6
  cout << "Great Choice. We still have a pretty good view on the activities that the gorillas are doing. We can take a photo or we can head back, What would you like to do? " << endl;
  cout << "1 - take a photo" << endl
  << "2 - head back soon" << endl;
  cin >> answer;
  return answer;
}
void optionLastMinPhotoOnRiver () {
cout << "I am glad you were able to take all the photos you wanted of the gorillas. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
void optionHeadBackOnRiver () {
cout << "The gorillas are now all drinking water and enjoying their bath. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazona and come back soon!" << endl;
}
int optionStayInAmazon (int& answer) { // this is 4
  cout << "Nice choice. While we are riding in the amazon, if you look up, you can see other creatures that hang in the branches of the trees. Other than snakes we can see a lot of different kinds of birds and monkeys. Which one would you like to follow? " << endl;
  cout << "1 - birds" << endl
  << "2 - monkeys" << endl;
  cin >> answer;
  return answer;
}
int optionFollowBirds (int& answer) { // this is 5
cout << "Since we are riding along the amazon floor and looking up can be hard to do, there are some species of birds that occasionally go to the ground to pick up seeds. Would you like to throw some seeds on the floor for the birds to get and another option is to hold out sugar water for the birds to come to." << endl;
cout << "1 - throw seeds on the amazon floor for the birds" << endl
<< "2 - feed the birds sugar water" << endl;
cin >> answer;
return answer;
}
int optionThrowSeeds (int& answer) { // this is 6
cout << "Great choice. This helps the birds out a lot and we can see all them hurry down to get as many as possible. Choose which one you would like to do..." << endl;
cout << "1 - take a photo of the birds " << endl
<< "2 - watch them eat" << endl;
cin >> answer;
return answer;
}
void optionTakeAPhotoOfBird () {
cout << "I am glad you were able to take all the photos you wanted of the birds. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
void optionWatchBirdsEat () {
cout << "The birds are now all eating the seeds and enjoying their food. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazon and come back soon!" << endl;
}
int optionFeedBirdsSugarWater (int& answer) { // this is 6
cout << "Make sure you do not move while they take the mixer out of the cup in your hand. You can also set it down on the ground this there is too many birds trying to get it at one. You can take a photo of the birds or you can watch them eat, what would you like to do?" << endl;
cout << "1 - take a photo of the birds " << endl
<< "2 - watch them eat" << endl;
cin >> answer;
return answer;
}
void optionTakeAPhotoOfBirds () {
cout << "I am glad you were able to take all the photos you wanted of the birds. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
void optionWatchBirdsEatSugarWater () {
cout << "The birds are now all eating the seeds and enjoying their food. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazon and come back soon!" << endl;
}
int optionFollowMonkeys (int& answer) { // this is 5 
  cout << "There are many species of monkeys here in the amazon. They are some really large and some that are really small which are the ones who are faster at swings amongst the trees above. Which would you prefer to do?" << endl;
  cout << "1 - follow monkeys that we could see up close " << endl
  << "2 - follow monkeys that are in the distance" << endl;
  cin >> answer;
  return answer;
}
int optionFollowUpClose (int& answer) { // this is 6
cout << "We are riding up some that seem to be preoccupied on eating berries. This is good so we do not scare them away. We have a few buckets of berries in the back of the jeep to give them or you can take a photo." << endl;
cout << "1 - feed them berries" << endl
<< "2 - take a photo" << endl;
cin >> answer;
return answer;
}
void optionFeedMonkeyBerries () {
cout << "The monkeys are now all eating the berries and enjoying their food. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazon and come back soon!" << endl;
}
void optionTakePhotoOfMonkeys () {
cout << "I am glad you were able to take all the photos you wanted of the monkeys. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
int optionFollowMonkeysInDistance (int& answer) { // this is 6
cout << "The monekys seem to be sharing food and cleaning eachother. It is best to keep our distance since we only want to observe and disturb these animals. We can leave them some food to eat near by without disrupting them or you can take a photo. Which would you like to do?" << endl;
cout << "1 - leave them some food" << endl
<< "2 - take a photo" << endl;
cin >> answer;
return answer;
}
void optionLeaveMonkeysFood () {
cout << "The monkeys are now all eating the berries as well as other fruit and enjoying their food. It is time for the tour group to head back and end the tour. I hope you had a fun time exploring the amazon and come back soon!" << endl; 
}
void optionTakeOnePhotoOfMonkeys () {
cout << "I am glad you were able to take all the photos you wanted of the monkeys. Sadly this is the end of the tour of the amazon. I hope you had a fun time exploring and come back soon!" << endl;
}
int main() {
  int answer;
  printDescription();
  optionRuinsWildlife(answer);
  system("clear");
  if (answer == 1) { // 2
    optionPrymaidRemains(answer);
    system ("clear");
    if (answer == 1) { //3 
      optionPryamids(answer);
      system ("clear");
      if (answer == 1) { // 4
        optionInsidePryamid(answer);
        system ("clear");
        if (answer == 1) { // 5
          optionHotAirBalloonRide(answer);
          system ("clear");
          if (answer == 1) { // 6
            optionFloatToWaterFalls (answer);
            system ("clear");
            if (answer == 1) { // 7
              optionByAirBalloon ();
            }
            if (answer == 2) { // 7
              optionLandAndJeep ();
            }
          }
          if (answer == 2) { // 6
            optionKeepLookingAtNature (answer);
            system ("clear");
            if (answer == 1) { // 7
              optionGoFurther ();
            }
            if (answer == 2) { // 7
              optionGetSomePictures ();
            }
          }
        }
        if (answer == 2) { // 5
          optionStayOnGround(answer);
          system ("clear");
          if (answer == 1) { // 6
            optionLastMinJeepRide (answer);
            system ("clear");
          if (answer == 1) { // 7
            optionScenicRoute ();
          }
          if (answer == 2) { // 7
            optionQuickWayBack ();
          }
          }
          if (answer == 2) { // 6
            optionLookAtStatues (answer);
            system ("clear");
            if (answer == 1) { // 7 
              optionPhotoWithStatue ();
            }
            if (answer == 2) { // 7 
              optionPhotoWithPryamid ();
            }
          }
        }
      }
      if (answer == 2) { // 4
        optionTakeAPhoto(answer);
        system ("clear");
        if (answer == 1) { // 5 
          optionElephantRide (answer);
          system ("clear");
          if (answer == 1){ // 6 
            optionPlayWithElephants (answer);
            system("clear");
            if (answer == 1) { // 7 
              optionGiveElephantSnack ();
            }
            if (answer == 2) { // 7 
              optionDistractWithPeanuts ();
            }
          }
          if (answer == 2) { // 6 
            optionFeedElephants (answer);
            system ("clear");
            if (answer == 1) { // 7 
              optionFeedPeanuts ();
            }
            if (answer == 2) { //7 
              optionFeedBananas ();
            }
          }
        } 
        if (answer == 2) { // 5 
          optionFeedAllElephants (answer);
          system ("clear");
          if (answer == 1) { // 6 
            optionFeedElephantPeanuts (answer);
            system ("clear");
            if (answer == 1) { // 7 
              optionGiveThemYourSnack ();
            }
            if (answer == 2) { // 7 
              optionGiveMorePeanuts ();
            }
          }
          if (answer == 2) { // 6 
            optionFeedElephantsBananas (answer);
            system ("clear");
            if (answer == 1 ) { // 7
            optionDistractThemWithBananas ();
            }
            if (answer == 2) { // 7
            optionGiveThemYourSnackNotABanana ();
            }
          }
        }
      }
  } 
  else if (answer == 2) { // 3
      optionReamins(answer);
      system ("clear");
    if (answer == 1) { // 4
      optionRemainsCave(answer);
      system ("clear");
      if (answer == 1) { // 5  
        optionLookAtCrystals (answer);
        system("clear");
        if (answer == 1) { // 6 
          optionDigForCrystals (answer);
          system("clear");
          if (answer == 1) { // 7 
            optionKeepGoingOnCrystal ();
          }
          if (answer == 2) { // 7 
            optionStartOnNewCrystal ();
          }
        }
        if (answer == 2) { // 6 
          optionGoingBackOutsideCave (answer);
          system ("clear");
          if (answer == 1) { // 7
            optionGoToRiver();
          }
          if (answer == 2) { // 7
            optionGoBackForLastJeepRide ();
          }
        }
      }
    }
    if (answer == 2) { // 4
      optionJumpInWater(answer);
      system ("clear");
      if (answer == 1) { // 5 doing rn 
        optionClimbRocks (answer);
        system ("clear");
        if (answer == 1) { // 6
          optionFeedBirds (answer);
          system ("clear");
          if (answer == 1) { // 7
            optionClimbALittleMore ();
          }
          if (answer == 2) { // 7
            optionGoBackNow ();
          }
        }
        if (answer == 2) { // 6 
          optionJumpOffLedgeIntoWater (answer);
          system("clear");
          if (answer == 1) { // 7 
            optionTakeARock ();
          }
          if (answer == 2) { // 7
            optionTakeFlower ();
          }
        }
      }
      if (answer == 2) { // 5 
        optionTakeAnotherJumpInWater (answer);
        system ("clear");
        if (answer == 1) { // 6
          optionGiveBananas (answer);
          system ("clear");
          if (answer == 1) { // 7
            optionLeaveBananas ();
          }
          if (answer == 2) { // 7
            optionLeaveRestOfBananas ();
          }
        }
        if (answer == 2) { // 6
          optionGiveMangos (answer);
          system("clear");
          if (answer == 1) { // 7
            optionLeaveMangos ();
          }
          if (answer == 2) {
            optionLeaveRestOfMangos();
          }
        }
      }
    }
  }
}
if (answer == 2){ // 2
    optionTigersSnakes(answer);
    system ("clear");
  if (answer == 1) { // 3 doing rn 
      optionTigers(answer);
      system ("clear");
      if (answer == 1) { // 4
        optionFollowTigerToCubs (answer);
        system("clear");
        if (answer == 1) { // 5
          optionGoSeeAnimals (answer);
          system ("clear");
          if (answer == 1) { // 6
            optionWatchThemEat (answer);
            system("clear");
            if (answer == 1) { // 7
            optionTakePhotoOfGorillas ();
            }
            if (answer == 2) { // 7
              optionGoBackRn ();
            }
          }
          if (answer == 2) { // 6
            optionFeedGorillasMoreBananas (answer);
            system ("clear");
            if (answer == 1) { // 7
              optionGiveGorillasMoreBananas ();
            }
            if (answer == 2) { // 7
              optionLeaveGorillasBananas ();
            }
          }
        }
      }
      if (answer == 2) { // 4
        optionTigerApproachingJeep (answer);
        system("clear");
        if (answer == 1) { // 5
          optionWatchElephantsOnly (answer);
          system("clear");
          if (answer == 1) { // 6
            optionTakePhotoOfElephants (answer);
            system("clear");
            if (answer == 1) { // 7
              optionTakeOneLastPhotoOfElephant ();
            }
            if (answer == 2) { // 7
              optionWatchAndGoBack ();
            }
          }
          if (answer == 2) { // 6
            optionGetOutOfJeepDistance (answer);
            system("clear");
            if (answer == 1) { // 7
              optionTakeACloserPhoto ();
            }
            if (answer == 2) {
              optionWatchElephantsPlay ();
            }
          }
        }
        if (answer == 2) { // 5 doing rn 
          optionGetCloserToElephants (answer);
          system("clear");
          if (answer == 1) { // 6
            optionWhatToFeedElephants (answer);
            system("clear");
            if (answer == 1) { // 7
            optionFeedElephantsTheMangos ();
            }
            if (answer == 2) { // 7
            optionFeedElephantsTheWatermelon ();
            }
          }
          if (answer == 2) { // 6
            optionWatchElephantsOnlyThere (answer);
            system("clear");
            if (answer == 1) { // 7
              optionTakeAPhotoBetterOfElephants ();
            }
            if (answer == 2) { // 7 
              optionElephantWatching ();
            }
          }
        }
      }
  }
  if (answer == 2) { // 3
      optionSnakes(answer);
      system("clear");
    if (answer == 1) { // 4
      optionRiverSnakes (answer);
      system ("clear");
      if (answer == 1) { // 5
        optionWaitToSeeARiverSnake (answer);
        system ("clear");
        if (answer == 1) { // 6
          optionWaitALittleLonger (answer);
          system ("clear");
          if (answer == 1) { // 7
          optionTakeARockFromRiver ();
          }
          if (answer == 2) { // 7
          optionTakeFlowerByRiver ();
          }
        }
        if (answer == 2) { // 6
          optionTakeAPhotoOfOtherCreatures (answer);
          system ("clear");
          if (answer == 1) { // 7
          optionFavAnimalFrog ();
          }
          if (answer == 2) { // 7
          optionFavAnimalBird ();
          }
        }
      }
      if (answer == 2) { // 5
        optionRideAlongRiver (answer);
          system ("clear");
        if (answer == 1) { // 6
          optionGetCloserOnRiver (answer);
          system ("clear");
          if (answer == 1) { // 7
          optionWatchFromDistOnRiver ();
          }
          if (answer == 2) { // 7
          optionTakePhotoFromDistOnRiver ();
          }
        }
        if (answer == 2) { // 6
          optionKeepDistOnRiver (answer);
          system ("clear");
          if (answer == 1) { // 7
            optionLastMinPhotoOnRiver ();
          }
          if (answer == 2) { // 7
            optionHeadBackOnRiver ();
          }
        }
      }
    }
    if (answer == 2) { // 4
        optionStayInAmazon (answer);
        system ("clear");
      if (answer == 1) { // 5
        optionFollowBirds (answer);
        system ("clear");
        if (answer == 1) { // 6
        optionThrowSeeds (answer);
        system ("clear");
          if (answer == 1) { // 7
          optionTakeAPhotoOfBird ();
          }
          if (answer == 2) { // 7
          optionWatchBirdsEat ();
          }
        }
        if (answer == 2) { // 6
        optionFeedBirdsSugarWater (answer);
        system ("clear");
          if (answer == 1) { // 7
          optionTakeAPhotoOfBirds ();
          }
          if (answer == 2) { // 7
          optionWatchBirdsEatSugarWater ();
          }
        }
      }
      if (answer == 2) { // 5
        optionFollowMonkeys (answer);
        system ("clear");
        if (answer == 1) { // 6
          optionFollowUpClose (answer);
          system ("clear");
          if (answer == 1) { // 7
          optionFeedMonkeyBerries();
          }
          if (answer == 2) { // 7
          optionTakePhotoOfMonkeys ();
          }
        }
        if (answer == 2) { // 6
          optionFollowMonkeysInDistance (answer);
          system ("clear");
          if (answer == 1) { // 7
          optionLeaveMonkeysFood ();
          }
          if (answer == 2) { // 7
          optionTakeOnePhotoOfMonkeys ();
          }
        }
      }
    }
  }
}
 
 
 
  
}
