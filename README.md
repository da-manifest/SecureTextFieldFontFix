To turn off secure entry & keep a custom font:

passwordTextField.isSecureTextEntry = false

var tmp = passwordTextField.text!

passwordTextField.attributedText = NSAttributedString(string: tmp)
