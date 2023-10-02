<h1>hw1</h1>
<table>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/ctwoc111/YZU_SwiftUI_1101406/main/stevejob_hw1.png">
    </td>
    <td>
      ```swift
      
      import SwiftUI

      struct ContentView: View {
          var body: some View {
              Image("SteveJob")
                  .resizable()
                  .aspectRatio(contentMode: .fill)
                  .overlay(
                      Text("no pain no gain！！")
                          .fontWeight(.heavy)
                          .lineSpacing(15)
                          .foregroundColor(.white)
                          .frame(width: 200, height: 80, alignment: .center)
                          .background(Color.gray)
                          .cornerRadius(15)
                          .opacity(0.9)
                      ,
                      alignment: .bottom
                  )
              
          }
      }

      
      ```
    </td>
  </tr>
</table>
