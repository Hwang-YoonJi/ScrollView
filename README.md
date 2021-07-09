# React Native - ScrollView
ScrollView Study :)

## Demo

<img src="https://user-images.githubusercontent.com/63582123/125054601-5d268100-e0e1-11eb-835e-f86a86fa11ce.gif" width="347" height="599">

## Usage

### App.js

```jsx
import React from 'react';
import { StyleSheet, Text, SafeAreaView, ScrollView, StatusBar } from 'react-native';

const App = () => {
  return (
    <SafeAreaView style={styles.container}>
      <Text style={styles.title}>♬ 비스트 - 비가 오는 날엔 ♬</Text>
      <ScrollView style={styles.scrollView}>
        <Text style={styles.text}>
          세상이 어두워지고{"\n"}조용히 비가 내리면{"\n"}여전히 그대로{"\n"}오늘도 어김없이 난{"\n"}
          벗어나질 못하네{"\n"}너의 생각 안에서{"\n"}이제 끝이라는 걸 알지만{"\n"}
          미련이란 걸 알지만{"\n"}이제 아닐 걸 알지만{"\n"}그까짓 자존심에{"\n"}널 잡지 못했던 내가{"\n"}
          조금 아쉬울 뿐이니까{"\n"}비가 오는 날엔 나를 찾아와{"\n"}밤을 새워 괴롭히다{"\n"}
          비가 그쳐가면 너도 따라서{"\n"}서서히 조금씩 그쳐가겠지{"\n"}취했나 봐{"\n"}그만 마셔야 될 것 같애{"\n"}
          비가 떨어지니까{"\n"}나도 떨어질 것 같애{"\n"}뭐 네가 보고 싶다거나{"\n"}그런 건 아냐{"\n"}
          다만 우리가 가진 시간이 좀{"\n"}날카로울 뿐{"\n"}네가 참 좋아했었던 이런 날이면{"\n"}
          아직 너무 생생한{"\n"}기억을 꺼내놓고{"\n"}추억이란 덫에{"\n"}일부러 발을 들여놔{"\n"}
          벗어나려고 발버둥조차{"\n"}치지 않아{"\n"}이제 너를 다 지워냈지만{"\n"}모두 다 비워냈지만{"\n"}
          또다시 비가 내리면{"\n"}힘들게 숨겨놨던{"\n"}너의 모든 기억들이{"\n"}다시 돌아와 널 찾나 봐{"\n"}
          비가 오는 날엔 나를 찾아와{"\n"}밤을 새워 괴롭히다{"\n"}비가 그쳐가면 너도 따라서{"\n"}
          서서히 조금씩 그쳐가겠지{"\n"}너에게로{"\n"}이젠 돌아갈 길은 없지만{"\n"}지금 행복한 너를 보며{"\n"}
          난 그래도 웃어볼게{"\n"}널 잡을 수 있었던{"\n"}힘이 내겐 없었으니까{"\n"}비가 오는 날엔 나를 찾아와{"\n"}
          밤을 새워 괴롭히다{"\n"}비가 그쳐가면 너도 따라서{"\n"}서서히 조금씩 그쳐 가겠지{"\n"}
          어차피 끝나버린 걸 이제 와{"\n"}어쩌겠어{"\n"}뒤늦게 후회나 하는 거지{"\n"}덜떨어진 놈처럼{"\n"}
          비는 항상 오니까{"\n"}계속 반복되겠지{"\n"}그치고 나면 그제서야{"\n"}나도 그치겠지{"\n"}
          비는 항상 오니까{"\n"}계속 반복되겠지{"\n"}그치고 나면 그제서야{"\n"}나도 그치겠지
        </Text>
      </ScrollView>
    </SafeAreaView>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: "center",
    alignItems: "center",
    paddingTop: StatusBar.currentHeight,
    backgroundColor: '#82b1ff',
  },
  scrollView: {
    flexGrow: 1,
    backgroundColor: '#82b1ff',
    marginHorizontal: 5,
  },
  title: {
    fontSize: 30,
    fontWeight: 'bold',
  },
  text: {
    fontSize: 20,
  },
});

export default App;
```