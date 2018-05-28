

### Class 0528 Story Board 사용 코드

//
//  ViewController.swift
//  Class0528_003
//
//  Created by Youngseok Kim on 2018. 5. 28..
//  Copyright © 2018년 Youngseok Kim. All rights reserved.
//

import UIKit

class ViewController: UIViewController {
    
    var ctn: Int = 0
    
    @IBOutlet weak var ButtonDidTap: UIButton!
    
    @IBAction func ButtonAct(_ sender: Any) {
        print("Action")
//        BtnCount.setTitle("ASDF", for: .normal)
        
        ctn += 1
        BtnCount.setTitle("\(ctn)", for: .normal)
        BtnCount.backgroundColor=UIColor.red
        
    }
    
    
    @IBOutlet weak var BtnCount: UIButton!
    
    
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }


}

