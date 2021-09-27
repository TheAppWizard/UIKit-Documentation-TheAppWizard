# UIKit-Documentation-TheAppWizard

## UIKit-Alert
```
    @IBAction func showAlert(){
    
        let alert = UIAlertController(
            title: "Hello Alert",
            message: "Alert Message",
            preferredStyle: .alert
        )
        
        let action = UIAlertAction(
            title: "Awesome Alert", style: .default, handler: nil
            
        )
        
        alert.addAction(action)
        present(alert,animated: true,completion: nil)
        
    }
```

