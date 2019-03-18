# Branches:

### 1_VoiceRecord
> https://classroom.udacity.com/courses/ud585

> 1. UIViewController holds different views.
2. Segue means transition, it is to connect views to ViewController, ViewController to ViewController.

>3. UINavigationController hosts stack of UIViewControllers. 
4. IBACTION - Reaching from UI element to Code. (usally drap Segue to bottom of Code). 
5. IBOutlet - Reaching from Code to UI element. (usally drap Segue to top of Code)

>6. UIKitFramework consists of different classes (like UIViewController, UIButton, UILabel,...)
7. Changeing class name must be done at 3 places (a) file name (b) class name (c) ViewController Identity Inspector.

>8. To know when the Audio has finished Recording and saving to wav file, we use Delegate.
 Here, AVAudioRecorderDelegate
 We mention this protocol, and mention that RecordSoundViewController will act as delate for AVAudioRecorderDelegate.

 >9. performSegue function to transfer the audio url file.

 >10. When Segue is called, there is a function thats triggered on the existing ViewController, to help prepare the segue - function thats called prepareForSegue.
 
 >extension PlaySoundsViewController: AVAudioPlayerDelegate
 https://youtu.be/mqhuDwywkc4