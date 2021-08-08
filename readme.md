#### Step 1: Install Android Enviroment
- Install Android Studio
- In Android Studio, open SDK Manager then install ndk
- Add `${your-sdk-folder}\Android\Sdk\platform-tools` to path => to use the build cmd
- Add user variable: ANDROID_HOME=`${your-sdk-folder}\Android\Sdk

#### Step 2: Install react native
- npm install -g react-native
- create project by: `npx react-native init AwesomeProject --version X.XX.X`
or if refer typescript: `npx react-native init AwesomeTSProject --template react-native-template-typescript`

#### Step 3: re-config build gradle to match with your enviroment in step 1
- See in the the 2nd commit of this repo

#### Step 4: config redux, library same as react web

#### Step 5: How to run

- npm run start => this will run metro bundler
- npm run android  => this will watch the metro bundler and deploy to android device.