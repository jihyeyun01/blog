import UIKit

class ViewController: UIViewController {

    @IBOutlet var sliderRed : UISlider!
    @IBOutlet var sliderGreen : UISlider!
    @IBOutlet var sliderBlue : UISlider!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        update()
    }
    
    @IBAction func changedSliderValue(sender:UISlider) {
        update()
    }
    func update() {
        self.view.backgroundColor = UIColor(
            red: CGFloat(sliderRed.value),
            green: CGFloat(sliderGreen.value),
            blue: CGFloat(sliderBlue.value),
            alpha: 1)
    }
}
