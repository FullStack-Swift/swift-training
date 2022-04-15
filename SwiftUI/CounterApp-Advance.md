
```swift
import SwiftUI

struct ContentView: View {
  
  @State private var count: Int = 0
  
  var body: some View {
    HStack {
      Button {
        count = count + 1
      } label: {
        Text("+")
      }
      Text("\(count)")
      Button {
        count = count - 1
      } label: {
        Text("-")
      }
    }
  }
}

struct ContentView_Previews: PreviewProvider {
  static var previews: some View {
    ContentView()
  }
}

```
