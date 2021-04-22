**Sergey Vyakulin**

### Contact Info:
 **Email:** Kefearisgood@gmail.com
 **Discord:** Каратист#6154


### Summary:
My goal is to become a mobile developer and create my own apps.

### Skills:
* Git
* Swift
* OOP
* Firebase
* MVC, MVP, MVVM, CleanSwift Architectures

### Code examples: 
 
 @objc private func signOut() {
     let alertController = UIAlertController(title: nil, message: "Are you sure want to sin out?", preferredStyle: .alert)
     alertController.addAction(UIAlertAction(title: "Cancel", style: .cancel, handler: nil))
     alertController.addAction(UIAlertAction(title: "Sign Out", style: .destructive, handler: { (_) in
         do{
             try Auth.auth().signOut()
             UIApplication.shared.keyWindow?.rootViewController = AuthViewController()
         } catch {
             print("Error signing out: \(error.localizedDescription)")
         }
     }))
     present(alertController, animated: true, completion: nil)
 }



### Education:
2017 - Samara State University of Economics
2014 - Samara State Technical University

### Language:
* English A2
