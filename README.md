import SwiftUI

struct ContentView: View {
    var body: some View {
        VStack {
            Text("Welcome to Flex Score!")
                .font(.largeTitle)
                .bold()
                .padding()

            Text("Track your progress with AI-powered fitness recommendations")
                .font(.subheadline)
                .padding()

            Button(action: {
                // Add action for taking body picture
            }) {
                Text("Get Started")
                    .padding()
                    .background(Color.blue)
                    .foregroundColor(.white)
                    .cornerRadius(8)
            }
        }
    }
}

@main
struct FlexScoreApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
