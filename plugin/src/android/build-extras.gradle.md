repositories{    
  jcenter()
  flatDir {
      dirs 'libs'
   }
}

dependencies {
   compile(name:'estimote-sdk', ext:'aar')
}
