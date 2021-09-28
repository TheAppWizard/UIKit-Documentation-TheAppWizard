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

## UIKit-Slider
```
 @IBAction func sliderMoved(_ slider : UISlider){
        print("The Value of Slider is : \(slider.value)")
    }
```
<img width="834" alt="UIKIt-Slider" src="https://user-images.githubusercontent.com/70090469/134944158-381736ed-3f14-4610-8bde-c56b00031e26.png">

## UIKit-Slider with Alert
```
 //Slider Current Value Integer
 var currentValue: Int = 0
 
 @IBAction func showAlert(){
        let message = "The value of the Slider is : \(currentValue)"
        
        
        let alert = UIAlertController(
            title: "Slider Value",
            message: message,
            preferredStyle: .alert
        
        )
        
        let action = UIAlertAction(
            title: "OK",
            style: .default,
            handler: nil
        )
        
        alert.addAction(action)
        present(alert, animated: true, completion: nil)
        
    }
    
    
    @IBAction func sliderMoved(_ slider : UISlider){
        currentValue = lroundf(slider.value)
    }
 

```




