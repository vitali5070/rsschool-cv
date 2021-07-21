1. **Vitali Nabarouski**
2. - *E-mail:* **naborovski@ya.ru**
   - *mob.:* **+375(25) 756-30-13**
   - *telegram:* **@vitali5070**
3. ***Good afternoon. My name is Vitaly Naborovsky. I was born on September 25, 1992 in Minsk, Belarus. 
    At school, I got interested in technology and gadgets. I began to learn the language of C++ and HTML.
    I liked creating websites and I began to learn this language very deeply after some time. At the same time,
    I was forced to learn CSS and PHP. I created forums and custom websites as a freelance developer. 
        After school, I went to a technical univercity. But I was forced to graduate after the first semester due to financial difficulties. 
        The next 10 years I worked in various restaurants and bars in my city. For 10 years there were a lot of interesting projects in the 
        restaurant business. At some point, I realized that I was not interested in further development. So I decided to study Swift on my own.
        I have been following this programming language since it was announced at the presentation. The whole ecosystem of Apple is close to me,
        so I chose this path without even thinking about it. As I was getting deeper into the language, I realized that I also needed to learn 
        Objective C. Parallel to my studies I started to look for a job as an IOS Junior Developer. Unfortunately there was no vacancy, 
        so I decided to take a course at Rolling Scopes, because I've heard only positive feedbacks. 
      This is my story.***
  4. **HTML, PHP, a little Swift (UIKit, CoreData, MapKit, REALM, FireBase), start to learn Objective C.**
  5. **A little bit of my code:**
        private func setupViews(){
            
        let collectionViewSizeHeight = mainView.bounds.size.height / 2
            
            view.addSubview(collectionView)
            
            signOutButton.topAnchor.constraint(equalTo: mainView.topAnchor, constant: 20).isActive = true
            signOutButton.trailingAnchor.constraint(equalTo: mainView.trailingAnchor, constant: 20).isActive = true
        
        collectionView.centerXAnchor.constraint(equalTo: mainView.centerXAnchor).isActive = true
        collectionView.topAnchor.constraint(equalTo: signOutButton.bottomAnchor, constant: 12).isActive = true
        collectionView.heightAnchor.constraint(equalToConstant: collectionViewSizeHeight).isActive = true
        collectionView.widthAnchor.constraint(equalToConstant: mainView.bounds.size.width).isActive = true
            
            buttonsStack.topAnchor.constraint(equalTo: collectionView.bottomAnchor, constant: 12).isActive = true
            buttonsStack.leadingAnchor.constraint(equalTo: mainView.leadingAnchor, constant: 40).isActive = true
            buttonsStack.trailingAnchor.constraint(equalTo: mainView.trailingAnchor, constant: 40).isActive = true
            buttonsStack.bottomAnchor.constraint(equalTo: mainView.bottomAnchor, constant: -10).isActive = true
        
            
        collectionView.set(cells: ProgramModel.fetchProgramData())
  }

 6. **Practice new topics. Personal challenges. Creating my own application for the restaurant business.**
 7. **Hight school.**
 8. **Conversations with guests at the bar. Internet articles.**
