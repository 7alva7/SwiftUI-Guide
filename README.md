# SwiftUI-Guide
![image](https://github.com/fzhlee/SwiftUI-Guide/blob/master/images/swiftui-logo.png)<br/>
图片来源：developer.apple.com
<br/><br/>
**SwiftUI<br/>
更好的应用，更少的代码。<br/>
SwiftUI是一种创新、简单的iOS开发中的界面布局方案，可以通过Swift语言的强大功能，在所有的Apple平台上快速构建用户界面。 仅使用一组工具和API为任何Apple设备构建用户界面。 <br/>
SwiftUI具有易于阅读和自然编写的声明式Swift语法，可与新的Xcode设计工具无缝协作，使您的代码和设计完美同步。 <br/>
自动支持动态类型、暗黑模式、本地化和可访问性，意味着您的第一行SwiftUI代码已经是您编写过的最强大的UI代码了。**
<br/>

---

实用快捷键<br/>
Command + Option + Enter : 打开或关闭预览窗口<br/>
Command + Option + P : 刷新预览窗口<br/>

---

<br/>
SwiftUI的80节教程及源码<br/>
所有课程基于Xcode 11 beta5，并在Xcode 11 beta5上编译通过。<br/>
当Xcode11正式版发布之后，会更新所有源码，以适配Xcode 11正式版。<br/>
<br/>
iOS开发相关互动课程列表，手把手学习iOS开发，App Store免费下载：<br/>
1、互动教程合集：https://apps.apple.com/cn/app/id1392811165<br/>
2、Xcode互动教程免费下载地址：https://itunes.apple.com/cn/app/id1063100471<br/>
3、Swift语言入门实例互动教程免费下载地址：https://itunes.apple.com/cn/app/id1320746678<br/>
4、app开发中的神兵利器免费下载地址：https://itunes.apple.com/cn/app/id1209739676<br/>
5、Objective-C语言应用开发互动教程免费下载地址：https://apps.apple.com/cn/app/id838877136<br/>
<br/>

---


![image](https://github.com/fzhlee/SwiftUI-Guide/blob/master/images/SwiftUI.png)
<br/>
图片来源：developer.apple.com<br/>

## 示例导航区：

* <span id="ExampleNavigator">第一章: 常用的Views</span>
	- [First Project](#1FirstProject)
	- [Text-BasicStyle](#2Text-BasicStyle)
	- [3Text-Paragraph](#3Text-Paragraph)
	- [4Text-Padding](#4Text-Padding)
	- [5Text-FullScreen](#5Text-FullScreen)
	- [6Text-DateFormatter](#6Text-DateFormatter)
	- [7Text-Append](#7Text-Append)
	- [8TextField](#8TextField)
	- [9TextField-SecureField](#9TextField-SecureField)
	- [10Button](#10Button)
	- [11Button-sheet](#11Button-sheet)
	- [12Spacer](#12Spacer)
	- [13Divider](#13Divider)
	- [14Image-Basic](#14Image-Basic)
	- [15Image-Style](#15Image-Style)
	- [16Image-Processing](#16Image-Processing)
	- [17Image-Blend](#17Image-Blend)
	- [18Image-Mask](#18Image-Mask)
	- [19Image-Transform](#19Image-Transform)
	- [20Image-Web](#20Image-Web)
	- [21Picker](#21Picker)
	- [22PickerDate](#22PickerDate)
	- [23Slider](#23Slider)
	- [24Stepper](#24Stepper)
	- [25Segment](#25Segment)
	- [26Toggle](#26Toggle)
	- [27TabView](#27TabView)
	- [28Webview](#28Webview)
	- [29MapView](#29MapView)
	- [30Shape-Circle](#30Shape-Circle)
	- [31Shape-Rectangle](#31Shape-Rectangle)
	- [32Shape-Path](#32Shape-Path)
	- [33GradientLinear](#33GradientLinear)
	- [34GradientAngular](#34GradientAngular)
	- [35GradientRadial](#35GradientRadial)
	<br/>

* <span id="Chapter2">第二章: Animation动画</span>
	- [1scaleEffect+default](#1scaleEffect+default)
	- [2Opacity+linear](#2Opacity+linear)
	- [3Offset+easeOut](#3Offset+easeOut)
	- [4RotationEffect+spring](#4RotationEffect+spring)
	- [5CombinedAnimation](#5CombinedAnimation)
	- [6SpeadAndDelay](#6SpeadAndDelay)
	- [7Repeating](#7Repeating)
	- [8ToggleVisibility](#8ToggleVisibility)
	- [9AsymmetricTransition](#9AsymmetricTransition)
	<br/>

* <span id="Image_D">第三章: Gesture手势</span>
	- [1TapGesture+Single tap](#1TapGesture+Singletap)
	- [2TapGesture+Double tap](#2TapGesture+Doubletap)
	- [3LongPressGesture](#3LongPressGesture)
	- [4RotationGesture](#4RotationGesture)
	- [5DragGesture](#5DragGesture)
	- [6LongPressGestureAndDragGesture](#6LongPressGestureAndDragGesture)
	<br/>

* <span id="Image_D">第四章: Layout布局</span>
	- [1Group](#1Group)
	- [2HSTack](#2HSTack)
	- [3VSTack](#3VSTack)
	- [4ZSTack](#4ZSTack)
	- [5List-Basic](#5List-Basic)
	- [6List-Insert](#6List-Insert)
	- [7List-Delete](#7List-Delete)
	- [8List-Move](#8List-Move)
	- [9List-DeleteAndMove](#9List-DeleteAndMove)
	- [10ScrollView-Vertical](#10ScrollView-Vertical)
	- [11ScrollView-Horizontal](#11ScrollView-Horizontal)
	- [12ScrollView-VerticalAndHorizontal](#12ScrollView-VerticalAndHorizontal)
	- [13Form-Basic](#13Form-Basic)
	- [14Form-Segment](#14Form-Segment)
	- [15Form-EnableDisable](#15Form-EnableDisable)
	- [16Form-ShowHide](#16Form-ShowHide)
	<br/>

* <span id="Image_D">第五章: DataFlow数据流</span>
	- [1NavigationLink](#1NavigationLink)
	- [2NavigationLinkAndGoBack](#2NavigationLinkAndGoBack)
	- [3PageNavigation](#3PageNavigation)
	- [4ObjectBinding](#4ObjectBinding)
	- [5EnviromentObject](#5EnviromentObject)
	- [6Show_Modal](#6Show_Modal)
	- [7Show-Alert](#7Show-Alert)
	- [8Show-ActionSheet](#8Show-ActionSheet)
	<br/>

* <span id="Image_D">第六章: More更多</span>
	- [1PreviewInNavigationView](#1PreviewInNavigationView)
	- [2Background](#2Background)
	- [3SizeCategory](#3SizeCategory)
	- [4PreviewDevice](#4PreviewDevice)
	- [5ViewAsProperties](#5ViewAsProperties)
	- [6onAppear-onDisappear](#6onAppear-onDisappear)
	- [7ColorScheme-LightAndDark](#7ColorScheme-LightAndDark)
	- [8AnyView](#8AnyView)
	- [9NavigationBarTitle](#9NavigationBarTitle)
	- [10NavigationItem](#10NavigationItem)
	- [11ViewModifier](#11ViewModifier)
	- [12Debug](#12Debug)
	<br/>
	
# 第一章 常用的Views<br/>
<h4 id="1FirstProject"> 第1节：SwiftUI空白项目的创建步骤：<h4>
1、打开Xcode，然后使用菜单命令:File > New > Project命令，打开项目创建窗口。<br/>
2、在项目模板选择窗口中，选择Single View App模板，然后点击Next按钮，进入下一步设置窗口。<br/>
3、在项目配置窗口中，需要勾选Use SwiftUI复选框，然后填写其它的配置选项，点击Next按钮，完成项目的创建。<br/>
4、SwiftUI项目创建完成之后，其项目结构和代码功能如下图所示：<br/>
	
![image](https://github.com/fzhlee/SwiftUI-Guide/blob/master/images/SwiftUIXcode.png) 

<br/>
5、项目导航区：<br/>

<table>
	<thead>
		<tr>
			<th>文件名称</th>
			<th>说明</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>AppDelegate.swift</td>
			<td>提供didFinishLaunchingWithOptions等方法，用来处理程序启动之后的事件，或者响应来自外部的事件。</td>
		</tr>
		<tr>
			<td>SceneDelegate.swift</td>
			<td>设置应用程序窗口的rootViewController，并指定使用哪个ContentView作为rootViewController的rootView。</td>
		</tr>
		<tr>
			<td>ContentView.swift</td>
			<td>项目的初始界面，用户界面上的可视控件可以放置在此文件中。</td>
		</tr>
		<tr>
			<td>Assets.xcassets</td>
			<td>项目的资源文件，您可以在此处放置项目中所需的图片、颜色等资源。</td>
		</tr>
		<tr>
			<td>LaunchScreen.storyboard</td>
			<td>用来配置项目启动过程中所显示的内容。</td>
		</tr>
		<tr>
			<td>Info.plist</td>
			<td>项目的配置属性文件，配置产品名称、版本号、Build号、Bundle Identifier等项目。</td>
		</tr>
	</tbody>
</table>

6、代码编辑器：<br/>
<ul>
  <li>SwiftUI使用声明性语法，因此开发者可以简单地说明用户界面应该做什么。</li>
  <li>例如，您可以编写需要包含文本字段的项目列表，然后描述每个字段的对齐方式，字体和颜色。</li>
  <li>您的代码比以前更简单，更易于阅读，从而节省您的时间和维护。</li>
</ul>
<br/>
7、ContentView.swift代码说明：<br/>

```swift
//导入SwiftUI框架
import SwiftUI 		             

//定义一个名为ContentView的结构体，该结构体遵循View协议，遵循View协议的元素才可以在SwiftUI框架中。就像在UIKit中，所见皆UIView一样，在SwiftUI中，所见皆是View。
struct ContentView: View {		 
//添加View协议中的body属性，在body属性中通过SwiftUI提供的各种布局控件，完成界面元素的搭建。关键词some表示返回的是某种View，但是SwiftUI不需要在意是具体的哪种View
    var body: some View {
    	//在屏幕上显示一个标签，标签的内容位于双引号之内
        Text("Hello World")
    }
}

//当处于Debug模式时，允许执行下方的代码
#if DEBUG
//定义一个遵循PreviewProvider的结构体，用于设置在右侧预览区需要实时预览的内容
struct ContentView_Previews: PreviewProvider {
//添加PreviewProvider协议中的previews属性，用来设置在实时预览区显示的内容
    static var previews: some View {
    	//设置在实时预览区显示ContentView结构体中的内容，您还可以在此设置预览的模拟器尺寸、是否Dark Mode等选项。
        ContentView()
    }
}
#endif
```

8、SceneDelegate.swift代码说明：<br/>

```swift
//使用此方法可以选择性地配置UIWindow窗口，并将其附加到提供的UIWindowScene
func scene(_ scene: UIScene, willConnectTo session: UISceneSession, options connectionOptions: UIScene.ConnectionOptions) {

        if let windowScene = scene as? UIWindowScene {
	    //初始化一个UIWindow窗口对象
            let window = UIWindow(windowScene: windowScene)
	    // 使用一个UIHostingController实例，作为该窗口的根 view controller
            window.rootViewController = UIHostingController(rootView: ContentView())
	    // 将新建的窗口作为当前程序的窗口对象
            self.window = window
	    // 将窗口作为主窗口并显示
            window.makeKeyAndVisible()
        }
    }
```

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="2Text-BasicStyle"> 第2节：Text-BasicStyle： </h4>
Text类似于UIKit中的UILabel，用于显示一行或多行的文字内容。<br/>
示例代码：<br/>

```swift
VStack{
    //Basic style
    Text("www.hdjc8.com")
	.bold()

    Text("www.hdjc8.com")
	.italic()

    Text("www.hdjc8.com")
	.underline()

    Text("www.hdjc8.com")
	.underline(true, color: .orange)

    Text("www.hdjc8.com")
	.strikethrough()

    Text("www.hdjc8.com")
	.strikethrough(true, color: .orange)

    Text("www.hdjc8.com")
	.foregroundColor(Color.orange)

    Text("www.hdjc8.com")
	.baselineOffset(CGFloat(5.0))
	.background(Color.orange)

     Text("www.hdjc8.com")
	 .background(Image("Picture"), alignment: .bottom)

    //Font
    VStack{
	Text("www.hdjc8.com")
	    .font(.footnote)

	Text("www.hdjc8.com")
	    .font(.system(size: 36))

	Text("www.hdjc8.com")
	    .font(.system(.title, design: .monospaced))

	Text("www.hdjc8.com")
	    .font(.custom("BradleyHandITCTT-Bold", size: 36))

	Text("www.hdjc8.com")
	    .fontWeight(Font.Weight.heavy)

	Text("www.hdjc8.com")
	    .fontWeight(Font.Weight.ultraLight)

    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/2Text-BasicStyle.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)



<h4 id="3Text-Paragraph"> 第3节：Text-Paragraph： </h4>
关于Text的段落属性：<br/>
示例代码：<br/>

```swift
VStack{

    Text("www.hdjc8.com")

    Text("www.hdjc8.com")
	.tracking(10)

    Text("www.hdjc8.com")
	.kerning(10)

    Text("www.hdjc8.com")
	.blur(radius: 1)

    Text("SwiftUI is an innovative, exceptionally simple way to build user interfaces across all Apple platforms with the power of Swift.")
	.lineSpacing(20)
//                .lineLimit(1)
	.lineLimit(nil)

    Text("www.hdjc8.com")
	.offset(x: 40, y: 0)

    Text("www.hdjc8.com")
	.frame(width: 200, height: 80, alignment: .bottomTrailing)
	.background(Color.orange)

    VStack{
	Text("www.hdjc8.com2")
	    .position(x: 50, y: 50)
	    .frame(width: 300, height: 100, alignment: .bottomTrailing)
	    .background(Color.orange)

	Text("Interactive\ntutorials\nfor\nXcode!")
	    .multilineTextAlignment(.center)
	    .lineLimit(4)

	Text("Hello\nInteractive Tutorials!").multilineTextAlignment(.leading)
    }

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/3Text-Paragraph.png"/>
</details>


[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)



<h4 id="4Text-Padding"> 第4节：Text-Padding： </h4>
复用padding特性，制作轮廓效果~<br/>
示例代码：<br/>

```swift
VStack{
    Text("www.hdjc8.com")
	.background(Color.black)
	.foregroundColor(.white)
	.padding(20)

    Text("www.hdjc8.com")
	.padding()
	.background(Color.black)
	.foregroundColor(.white)

    Text("Swift User Interface")
	.font(.largeTitle)
	.foregroundColor(.black)
	.padding(15)
	.background(Color.yellow)
	.padding(15)
	.background(Color.orange)
	.padding(10)
	.background(Color.red)
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/4Text-Padding.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)



<h4 id="5Text-FullScreen"> 第5节：Text-FullScreen： </h4>
通过edgesIgnoringSafeArea，忽略安全区域，使文本框撑满屏幕。<br/>
示例代码：<br/>

```swift
Text("Hello World")
    .frame(minWidth: 0, maxWidth: .infinity, minHeight: 0, maxHeight: .infinity)
    .background(Color.orange)
    .font(.largeTitle)
    .edgesIgnoringSafeArea(.all)
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/5Text-FullScreen.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="6Text-DateFormatter"> 第6节：Text-DateFormatter： </h4>
对文本中的日期内容进行格式化。<br/>
示例代码：<br/>

```swift
var now = Date()
static let dateFormatter: DateFormatter = {
let formatter = DateFormatter()
formatter.dateStyle = .long
return formatter
}()

var body: some View {

Text("The time is: \(now, formatter: Self.dateFormatter)")
    .font(.title)
    .padding()

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/6Text-DateFormatter.png"/>
</details>

<h4 id="7Text-Append"> 第7节：Text-Append： </h4>
添加扩展方法+，对文本View进行拼接，实现富文本的艺术效果。<br/>
示例代码：<br/>

```swift
Text("Interactive ")
    .foregroundColor(.yellow)
    .fontWeight(.heavy)
+ Text("tutorials ")
    .foregroundColor(.orange)
    .strikethrough()
+ Text("for ")
    .foregroundColor(.red)
    .italic()
+ Text("SwiftUI")
    .foregroundColor(.purple)
    .underline()
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/7Text-Append.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)

<h4 id="8TextField"> 第8节：TextField： </h4>
TextField类似于UIKit中的UITextField，用于实现用户的文字内容的输入。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var username : String
    @State var nickname : String
    
    var body: some View {
        
        VStack{
            
            Text("Your username is \(username)!")
            
            Text("Your nickname is \(nickname)!")
            
            TextField("User Name", text: $username, onEditingChanged: { (value) in
                print("onEditingChanged:\(self.username)")
            }) {
                print("onCommit:\(self.username)")
            }.textFieldStyle(RoundedBorderTextFieldStyle())
            
            TextField("Nick Name", text: $nickname)
                .textFieldStyle(RoundedBorderTextFieldStyle())
            
        }
        .padding()
        
    }
}

#if DEBUG
struct ContentView_Previews : PreviewProvider {
    
    static var previews: some View {
        ContentView(username: "", nickname: "")
    }
}
#endif
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/8TextField.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)

<h4 id="9TextField-SecureField"> 第9节：TextField-SecureField： </h4>
相当于UITexfield的secureTextEntry的属性设置为true时的情况。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var password : String
    
    var body: some View {
        
        VStack{
            
            Text("Your password is \(password)!")
            
            SecureField("Your password", text: $password) {
                print("Your password is \(self.password)!")
            }
            .textFieldStyle(RoundedBorderTextFieldStyle())
            
        }
        .padding()
        
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/9TextField-SecureField.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)

<h4 id="10Button"> 第10节：Button： </h4>
相当于UIKit中的UIButton控件，用于实现接收用户的点击事件。<br/>
示例代码：<br/>

```swift
VStack{

    Button("First button") {
	print("---First button action.")
    }

    Button(action: {
	print("---Second button action.")
    }) {
	Text("Second button")
    }

    Button(action: {
	print("---Third button action.")
    }) {
	Image(systemName: "clock")
	Text("Third button")
    }
    .foregroundColor(Color.white)
    .background(Color.orange)

    //padding for button : the tap area is wrong
    Button(action: {
	print("---padding for button.")
    }){
	Text("Default padding")
    }
    .padding()
    .background(Color.yellow)

    //padding for label : the tap area is correct!
    Button(action: {
	print("---padding for label.")
    }){
	Text("Default padding")
	    .padding()
	    .background(Color.yellow)
    }

    Button(action: {
	print("---Button with image.")
    }){
	HStack {
	    Image(systemName: "star")
	    Text("Button with image")
	}
	.padding()
	    .background(Color.yellow)
    }
    Button(action: {
	print("---modifier button")
    }){
	Text("modifier button")
	    .modifier(MyButtonStyle())
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/10Button.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)

<h4 id="11Button-sheet"> 第11节：Button-sheet： </h4>
当点击按钮时，弹出Modl模态窗口。<br/>
示例代码：<br/>

```swift
struct ContentView : View {

    @State var isPresented = false
    
    var body: some View {
        VStack{
            Button("Show modal") {
                self.isPresented = true
            }.sheet(isPresented: $isPresented, content: {
                MyDetailView(message: "Modal window")
            })
        }
    }
}

struct MyDetailView: View {
    let message: String

    var body: some View {
        VStack {
            Text(message)
                .font(.largeTitle)
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/11Button-sheet.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="12Spacer"> 第12节：Spacer： </h4>
Spacer是一个灵活的空间视图，它可以沿着包含堆栈布局的主轴进行扩展，如果不包含在堆栈中，则在两个x或y轴上进行扩展。<br/>
示例代码：<br/>

```swift
var body: some View {
        VStack{
            HStack {
                Image(systemName: "clock")
                Spacer()
           }
           .padding()
        
           HStack {
                Image(systemName: "clock")
                Spacer()
                Text("\(Date())")
           }
           .padding()
        
            HStack {
                 Image(systemName: "clock")
                 Spacer(minLength: 50)
                 Text("\(Date())")
            }
            .padding()
        }
    }
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/12Spacer.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="13Divider"> 第13节：Divider： </h4>
当Divider包含在VStack或YStack中时，Divider跨越堆栈的短轴延伸，或者当不在堆栈中时则进行水平分隔。<br/>
示例代码：<br/>

```swift
VStack{
    VStack {
	 Image(systemName: "clock")
	 Divider()
	 Text("\(Date())")
    }
    .padding()

    VStack {
	 Image(systemName: "clock")
	 Divider()
	    .background(Color.purple)
	    .scaleEffect(CGSize(width: 1, height: 10))
	 Text("\(Date())")
    }
    .padding()
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/13Divider.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="14Image-Basic"> 第14节：Image-Basic： </h4>
Image相当于UIKit中的UIImage控件，用于显示指定名称的图片，或者显示指定systemName的图标。<br/>
示例代码：<br/>

```swift
VStack{
            
    Image("girlPicture")

    Image(systemName: "arkit")
	.foregroundColor(.orange)
	.font(.system(size: 48))

    Image("girlPicture")
	.resizable()
	.aspectRatio(contentMode: .fit)
}
.padding()
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/14Image-Basic.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="15Image-Style"> 第15节：Image-Style： </h4>
设置图像的边框、不透明度、阴影等属性。<br/>
示例代码：<br/>

```swift
ScrollView{
     VStack{

	Image("girlPicture")
	    .border(Color.orange)

	Image("girlPicture")
	    .border(Color.orange, width: 10)

	Image("girlPicture")
	    .opacity(0.5)

	Image("girlPicture")
	    .shadow(radius: 10)

	Image("girlPicture")
	    .shadow(color: .purple, radius: 20, x: 20, y: 20)
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/15Image-Style.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="16Image-Processing"> 第16节：Image-Processing： </h4>
给图片进行图像颜色的设置：设置模糊效果、设置图片的亮度、反转图片的颜色、对比度等效果<br/>
示例代码：<br/>

```swift
ScrollView{
     VStack{
	Image("girlPicture")

	Image("girlPicture")
	    .blur(radius: CGFloat(2))

	Image("girlPicture")
	    .blur(radius: CGFloat(2), opaque: true)

	Image("girlPicture")
	    .brightness(0.2)

	Image("girlPicture")
	    .colorInvert()

	Image("girlPicture")
	    .colorMultiply(Color.yellow)

	Image("girlPicture")
	    .contrast(1.5)
    }

    VStack{
	Image("girlPicture")
	    .hueRotation(Angle.degrees(180))

	Image("girlPicture")
	    .saturation(10)

	Image("girlPicture")
	    .grayscale(5.5)

	Image("girlPicture")
	    .luminanceToAlpha()
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/16Image-Processing.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="17Image-Blend"> 第17节：Image-Blend： </h4>
在图像之间进行颜色像素之间的运算。<br/>
示例代码：<br/>

```swift
VStack{
            
    Image("girlPicture")
	.blendMode(.difference)

    ZStack{
	Image("texture")
	Image("girlPicture")
	    .blendMode(.multiply)
    }
}
.padding()
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/17Image-Blend.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="18Image-Mask"> 第18节：Image-Mask： </h4>
给图片添加遮罩效果。<br/>
示例代码：<br/>

```swift
VStack{

    Image("girlPicture")
	.clipShape(Circle())

    Image("girlPicture")
	.mask(Circle())

    Image("texture")
    .resizable()
    .frame(width: 300, height: 300)
    .mask(
	Text("SWIFT UI!")
	    .font(Font.system(size: 64).bold()))

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/18Image-Mask.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="19Image-Transform"> 第19节：Image-Transform： </h4>
给图像应用缩放、旋转等变形效果。<br/>
示例代码：<br/>

```swift
ScrollView{
            
    VStack{
	Image("girlPicture")
	    .scaleEffect(0.8)

	Image("girlPicture")
	    .scaleEffect(CGSize(width: 1.2, height: 1))

	Image("girlPicture")
	    .scaleEffect(x: 1.5, y: 1, anchor: UnitPoint.bottomLeading)
    }

     VStack{

	Image("girlPicture")
	     .rotationEffect(Angle.init(degrees: 90))

	Image("girlPicture")
	    .rotationEffect(Angle.init(degrees: 30), anchor: UnitPoint.init(x: 0, y: 0))

	Image("girlPicture")
	    .rotation3DEffect(Angle.init(degrees: 30), axis: (x: CGFloat(0.1), y: CGFloat(0.1), z: CGFloat(0)))

    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/19Image-Transform.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="20Image-Web"> 第20节：Image-Web： </h4>
异步加载网络图片。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State private var remoteImage : UIImage? = nil
    let placeholderOne = UIImage(named: "Picture")
    
    var body: some View {
        Image(uiImage: self.remoteImage ?? placeholderOne!)
            .onAppear(perform: fetchRemoteImage)
    }
    
    func fetchRemoteImage()
    {
        guard let url = URL(string: "http://hdjc8.com/images/logo.png") else { return }
        URLSession.shared.dataTask(with: url){ (data, response, error) in
            if let image = UIImage(data: data!){
                self.remoteImage = image
            }
            else{
                print(error ?? "")
            }
        }.resume()
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/20Image-Web.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="21Picker"> 第21节：Picker： </h4>
Picker相当于UIKit中的UIPickerView，用于实现若干项目的选择。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
     var fruits = ["Apple", "Banner", "Pear", "Watermelon"]
     var colors = [Color.blue, Color.orange, Color.red, Color.purple]
     @State private var selectedItem = 0

     var body: some View {
        VStack {
            
           Picker(selection: $selectedItem, label: Text("Fruits")) {
              ForEach(0 ..< fruits.count) {
                Text(self.fruits[$0]).tag($0).foregroundColor(self.colors[$0])
              }
           }
           Text("Your choice: ")
            + Text("\(fruits[selectedItem])").foregroundColor(self.colors[selectedItem])
        }
     }
}

```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/21Picker.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="22PickerDate"> 第22节：PickerDate： </h4>
PickerDate相当于UIKit中的UIDatePicker控件，用于实现时间和日期项目的选择。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    var myDateFormatter: DateFormatter {
        let formatter = DateFormatter()
        formatter.dateStyle = .long
        return formatter
    }

    @State var selectedDate = Date()

    var body: some View {
        VStack {
            DatePicker(selection: $selectedDate, displayedComponents: DatePickerComponents.hourAndMinute) {
                Text("Date")
            }
            
            DatePicker(selection: $selectedDate, displayedComponents: DatePickerComponents.date) {
                Text("Date")
            }

            DatePicker(selection: $selectedDate,in: Date()...Date().advanced(by: 7*24*3600), displayedComponents: [.date, .hourAndMinute]) {
                Text("Date")
            }

            Text("Your Choice: \(selectedDate, formatter: myDateFormatter)")
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/22PickerDate.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="23Slider"> 第23节：Slider： </h4>
Slider相当于UIKit中的UISlider，通过移动滑杆实现指定区域和间隔的数值的选择。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
     @State var temperature: Double = 0

       var body: some View {
           VStack {
                Slider(value: $temperature)
                Slider(value: $temperature, in: -20...40)
                Slider(value: $temperature, in: -20...40) { (item) in
                    print(item)
                }
                HStack{
                    Image(systemName: "sun.max")

                    Slider(value: $temperature, in: -20...40, step: 2) { (item) in
                        print(item)
                    }.accentColor(.pink).colorInvert()
                    
                   Image(systemName: "sun.max.fill")
                }.padding()

                Text("The temperature is \(Int(temperature)).")
           }
       }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/23Slider.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="24Stepper"> 第24节：Stepper： </h4>
Stepper步进器相当于UIKit中的UIStepper，用于实现数据的递增和递减。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
     @State var temperature: Double = 0

       var body: some View {
        
           VStack {
                Stepper(onIncrement: {
                    self.temperature += 1
                }, onDecrement: {
                    self.temperature -= 1
                }, label: { Text("Temperature: \(Int(temperature))") })
                
                Stepper(onIncrement: {
                    self.temperature += 1
                }, onDecrement: {
                    self.temperature -= 1
                }, onEditingChanged: { (item) in
                    print(item)
                }, label: { Text("Temperature: \(Int(temperature))") })
           
       }.padding()
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/24Stepper.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="25Segment"> 第25节：Segment： </h4>
Segment分段控件，类似于UIKit中的UISegmentedControl。分段控件提供一栏选项按钮，一次只能激活其中一个选项按钮。用于实现若干选项的单选。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    private var animals = ["🐶 Dog", "🐯 Tiger", "🐷 Pig"]
    var colors = [Color.yellow, Color.orange, Color.red, Color.purple]
    @State private var selectedAnimal = 0

    var body: some View {
        VStack {
            Picker(selection: $selectedAnimal, label: Text("animals")) {
               ForEach(0 ..< animals.count) {
                Text(self.animals[$0]).tag($0)
               }
            }.pickerStyle(SegmentedPickerStyle())
            Text("Your choice: \(animals[selectedAnimal])")
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/25Segment.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="26Toggle"> 第26节：Toggle： </h4>
Toggle相当于UIKit中的UIToggle，用于实现选项开关(开户或关闭)的功能。<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    @State var showNotification = true

    var body: some View {
        VStack {
            Text("Show Notification: ")
            + Text("\(self.showNotification.description)")
                .foregroundColor(.green)
                .bold()
                
            
            Toggle(isOn: $showNotification) {
                Text("Show notification:")
            }.padding()
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/26Toggle.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="27TabView"> 第27节：TabView： </h4>
TabView相当于UIKit中的UITabBarController，用于实现标签视图集。<br/>
示例代码：<br/>

```swift
var body: some View {
	TabView {
	    Text("The home page.")
		.font(.system(size: 36))
		.tabItem({
		    Image(systemName: "house")
		    Text("Home") })
		.tag(0)

	    Text("The settings page")
		.font(.system(size: 36))
		.tabItem({
		    Image(systemName: "gear")
		    Text("Settings")
		})
		.tag(1)
	}
    }
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/27TabView.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="28Webview"> 第28节：使用UIKit中的Webview： </h4>
SwiftUI并没有包含WebView，这里通过遵循UIViewRepresentable协议，在SwiftUI中集成UIKit中的WKWebView。<br/>
示例代码：<br/>

```swift
import SwiftUI
import WebKit

struct ContentView : UIViewRepresentable {
    
    func makeUIView(context: UIViewRepresentableContext<ContentView>) -> WKWebView {
        return WKWebView()
    }
    
    func updateUIView(_ uiView: WKWebView, context: UIViewRepresentableContext<ContentView>) {
        let request = URLRequest(url:URL(string: "https://apple.com")!)
        uiView.load(request)
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/28Webview.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="29MapView"> 第29节：MapView： </h4>
SwiftUI并没有包含MapView，这里通过遵循UIViewRepresentable协议，在SwiftUI中集成UIKit中的WKMapView。<br/>
示例代码：<br/>

```swift
import SwiftUI
import MapKit

struct ContentView : UIViewRepresentable {
    
    func makeUIView(context: UIViewRepresentableContext<ContentView>) -> MKMapView {
        return MKMapView()
    }
    
    func updateUIView(_ uiView: MKMapView, context: UIViewRepresentableContext<ContentView>) {
        uiView.showsUserLocation = true
        uiView.mapType = MKMapType.satellite
        
        let coordinate2D = CLLocationCoordinate2D(latitude: 39.915352, longitude: 116.397105)
        let zoomLevel = 0.02
        let region = MKCoordinateRegion(center: coordinate2D, span: MKCoordinateSpan(latitudeDelta: zoomLevel, longitudeDelta: zoomLevel))
        uiView.setRegion(uiView.regionThatFits(region), animated: true)
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/29MapView.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="30Shape-Circle"> 第30节：Shape-Circle： </h4>
使用Circle绘制圆，并设置圆形的填充颜色、显示区域等属性。<br/>
示例代码：<br/>

```swift
VStack{
    Circle()
    Circle()
	.fill(Color.orange)
	.frame(width: 200, height: 200)
    ZStack {
       Circle().fill(Color.purple)
       Circle().fill(Color.yellow).scaleEffect(0.8)
       Circle().fill(Color.orange).scaleEffect(0.6)
    }
    Rectangle()
    Rectangle()
	.fill(Color.orange)
	.frame(width: 200, height: 200)
    ZStack {
       Rectangle().fill(Color.purple)
	.frame(width: 300, height: 200)

       Rectangle().fill(Color.yellow)
	.frame(width: 300, height: 200)
	.scaleEffect(0.8)

       Rectangle()
	.fill(Color.orange)
	.frame(width: 300, height: 200)
	.scaleEffect(0.6)
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/30Shape-Circle.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="31Shape-Rectangle"> 第31节：Shape-Rectangle： </h4>
使用Rectangle绘制矩形，使用RoundedRectangle绘制圆角矩形。<br/>
示例代码：<br/>

```swift
VStack{
            
    Rectangle()
    Rectangle()
	.fill(Color.orange)
	.frame(width: 200, height: 200)

    ZStack {
       Rectangle().fill(Color.purple)
	.frame(width: 300, height: 200)

       Rectangle().fill(Color.yellow)
	.frame(width: 300, height: 200)
	.scaleEffect(0.8)

       Rectangle()
	.fill(Color.orange)
	.frame(width: 300, height: 200)
	.scaleEffect(0.6)
    }

    RoundedRectangle(cornerRadius: 120)

    RoundedRectangle(cornerSize: CGSize(width: 100, height: 40)).frame(width: 300, height: 200)

    RoundedRectangle(cornerRadius: 100, style: RoundedCornerStyle.continuous)

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/31Shape-Rectangle.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="32Shape-Path"> 第32节：32Shape-Path： </h4>
使用Path，并配合move和addLine绘制自定义的图形<br/>
示例代码：<br/>

```swift
Path { path in
   path.move(to: CGPoint(x: 30, y: 0))
   path.addLine(to: CGPoint(x: 30, y: 200))
   path.addLine(to: CGPoint(x: 230, y: 200))
    path.addLine(to: CGPoint(x: 230, y: 0))
}

Path { path in
    path.addEllipse(in: CGRect(x: 100, y: 30, width: 200, height: 200))

    path.addRoundedRect(in: CGRect(x: 100, y: 120, width: 200, height: 200), cornerSize: CGSize(width: 10, height: 10))

    path.addEllipse(in: CGRect(x: 100, y: 210, width: 200, height: 200))
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/32Shape-Path.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="33GradientLinear"> 第33节：LinearGradien： </h4>
使用LinearGradien绘制线形颜色渐变的背景。<br/>
示例代码：<br/>

```swift
Text("SwifUI Gradient")
    .font(.system(size: 36))
    .padding()
    .foregroundColor(.white)
    .background(LinearGradient(gradient: Gradient(colors: [.orange, .red, .purple]), startPoint: .topLeading, endPoint: .bottomTrailing))

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/33GradientLinear.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="34GradientAngular"> 第34节：AngularGradient： </h4>
使用AngularGradient绘制角度颜色渐变的背景。<br/>
示例代码：<br/>

```swift
VStack{
    Text("SwifUI Gradient")
    .font(.system(size: 36))
    .padding()
    .foregroundColor(.white)
    .background(AngularGradient(gradient: Gradient(colors: [.orange, .red, .purple]), center: UnitPoint(x: 0.5, y: 0.5), angle: Angle.init(degrees: -45)))

    Text("SwifUI Gradient")
    .font(.system(size: 36))
    .padding()
    .foregroundColor(.white)
    .background(AngularGradient(gradient: Gradient(colors: [.orange, .red, .purple]), center: UnitPoint(x: 0.5, y: 0.5), startAngle: Angle.init(degrees: 0), endAngle: Angle.init(degrees: 0)))

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/34GradientAngular.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)


<h4 id="35GradientRadial"> 第35节：RadialGradient： </h4>
使用RadialGradient绘制径向颜色渐变的背景。<br/>
示例代码：<br/>

```swift
Text("SwifUI Gradient")
    .font(.system(size: 36))
    .padding()
    .foregroundColor(.white)
    .background(RadialGradient(gradient: Gradient(colors: [.orange, .red, .purple]), center: .init(x: 0.5, y: 0.5), startRadius: CGFloat(10), endRadius: CGFloat(120)))

}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/35GradientRadial.png"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#ExampleNavigator)

# 第二章 动画Animation<br/>
<h4 id="1scaleEffect+default"> 第1节：scaleEffect+default </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var factor: CGFloat = 1

    var body: some View {
        
        VStack{
            Image("logo")
                .scaleEffect(factor)
                .animation(.default)
            
            Divider().fixedSize()
            
            Button(action: {
                self.factor += 0.2
            }) {
                Text("Zoom in")
            }
        }
    }
}

```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/1scaleEffect+default.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="2Opacity+linear"> 第2节：Opacity+linear </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var factor: Double = 1
    @State var alpha: Double = 1

    var body: some View {
        Image("logo")
            .scaleEffect(CGFloat(factor))
            .opacity(alpha)
            .onTapGesture {
                withAnimation(.linear(duration: 1.0)) {
                    self.factor += 0.1
                    self.alpha -= 0.2
                }
            }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/2Opacity+linear.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)


<h4 id="3Offset+easeOut"> 第3节：Offset+easeOut </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var distance: Double = 0

    var body: some View {
        VStack{
            Image("logo")
                .offset(x: 0, y: CGFloat(distance))
                .animation(.easeOut(duration: 2))
            
            Divider().fixedSize()
            
            Button(action: {
                self.distance -= 120
            }) {
                Text("Move Effect")
            }
            
        }
        
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/3Offset+easeOut.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="4RotationEffect+spring"> 第4节：RotationEffect+spring </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var angle: Double = 0

    var body: some View {
        VStack{
            Image("logo")
            .rotationEffect(Angle.init(degrees: angle))
            .animation(.spring())
            
            Divider().fixedSize()
            
            Button(action: {
                self.angle += 90
            }) {
                Text("Rotation Effect")
            }
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/4RotationEffect+spring.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="5CombinedAnimation"> 第5节：CombinedAnimation</h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var radius: Double = 0
    @State var brightness: Double = 0

    var body: some View {
        VStack{
            Image("logo")
                .shadow(radius: CGFloat(radius))
                .brightness(brightness)
                .animation(.linear(duration: 2))
            
            Divider().fixedSize()
            
            Button(action: {
                self.radius += 10
                self.brightness = 1
            }) {
                Text("Move Effect")
            }
            
        }
        
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/5CombinedAnimation.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="6SpeadAndDelay"> 第6节：SpeadAndDelay </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    @State var factor: Double = 1.0
    
    var animation: Animation {
        Animation.linear(duration: 1)
//            .speed(1)
//            .speed(5)
            .delay(2)
    }

    var body: some View {
        VStack{
            Image("logo")
            .scaleEffect(CGFloat(factor))
            .animation(animation)
            
            Divider().fixedSize()
            
            Button(action: {
                self.factor += 0.2
            }) {
                Text("Zoom In Effect")
            }
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/6SpeadAndDelay.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="7Repeating"> 第7节：Repeating </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var angle: Double = 0
    
    var animation: Animation {
        Animation.spring()
             .repeatForever()
//            .repeatForever(autoreverses: false)
//            .repeatCount(3)
    }

    var body: some View {
        VStack{
            Image("logo")
                .rotationEffect(Angle.init(degrees: angle))
                .animation(animation)
            
            Divider().fixedSize()
            
            Button(action: {
                self.angle += 45
            }) {
                Text("Repeat Forever Effect")
            }
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/7Repeating.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="8ToggleVisibility"> 第8节：ToggleVisibility </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    
    @State var showingPassword = false
    @State var password = ""

    var body: some View {
        
        VStack {
            Toggle(isOn: $showingPassword.animation(.spring())) {
                Text("Toggle Password")
            }

            if showingPassword {
                TextField("Password", text: $password)
                    .padding()
                    .border(Color.green, width: 1)
            }
        }
        .padding()
    }
}

```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/8ToggleVisibility.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

<h4 id="9AsymmetricTransition"> 第9节：AsymmetricTransition </h4>
<br/>
示例代码：<br/>

```swift
struct ContentView : View {
    @State var showPicture = false

    var body: some View {
        VStack {
            Button(action: {
                withAnimation {
                    self.showPicture.toggle()
                }
            }) {
                Text("Show picture")
            }

            if showPicture {
//                Image("logo")
                
//                Image("logo")
//                    .transition(.move(edge: .top))
                
//                Image("logo")
//                    .transition(.scale(scale: 0))
                
//                Image("logo")
//                    .transition(.slide)
                
//                Image("logo")
//                    .transition(.asymmetric(insertion: .scale(scale: 0), removal: .slide))
                
                Image("logo")
                    .transition(AnyTransition.scale(scale: 0).combined(with:.slide))
            }
        }
    }
}
```

<details close>
  <summary>查看运行结果</summary>
<img width="100%" src="images/9AsymmetricTransition.gif"/>
</details>

[<img width="89" src="images/topIcon.png"/>](#Chapter2)

