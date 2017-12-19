# Huguette
echo "# Pello" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Anapello/Pello.git
git push -u origin master
pod 'Pageboy', '~> 2.0'
pod install
$ brew update
$ brew install carthage
github "uias/Pageboy" ~> 2.0
class PageViewController: PageboyViewController, PageboyViewControllerDataSource {

	override func viewDidLoad() {
		super.viewDidLoad()

		self.dataSource = self
	}
}

func numberOfViewControllers(in pageboyViewController: PageboyViewController) -> Int {
    return viewControllers.count
}
    
func viewController(for pageboyViewController: PageboyViewController,
                    at index: PageboyViewController.PageIndex) -> UIViewController? {
    return viewControllers[index]
}
    
func defaultPage(for pageboyViewController: PageboyViewController) -> PageboyViewController.Page? {
    return nil
}
func pageboyViewController(_ pageboyViewController: PageboyViewController,
                           willScrollToPageAt index: Int,
                           direction: PageboyViewController.NavigationDirection,
                           animated: Bool)
func pageboyViewController(_ pageboyViewController: PageboyViewController,
                           didScrollTo position: CGPoint,
                           direction: PageboyViewController.NavigationDirection,
                           animated: Bool)
  public func scrollToPage(_ pageIndex: PageIndex,
                            animated: Bool,
                            completion: PageTransitionCompletion? = nil)                
 public func currentViewController
public func  currentPosition
public func  showsPageControl

  
