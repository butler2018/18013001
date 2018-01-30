# 18013001

//計算到101的距離
     Location loc101 = new Location("LOC");
     loc101.setLatitude(25.0336);  //緯度
     loc101.setLongitude(121.5646); //經度

     float dist = location.distanceTo(loc101);
     Log.d("LOC","dist:" +dist);
