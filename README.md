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

<img width="885" alt="alert-uikit" src="https://user-images.githubusercontent.com/70090469/134934387-306749b5-ff95-4068-af3e-a24a5459c895.png">

## UIKit-Slider & Label
