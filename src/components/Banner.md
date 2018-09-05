# Banner

```.jsx
<Banner
  color='white'
  bg='darken'
  backgroundImage='https://images.unsplash.com/photo-1462331940025-496dfbfc7564?w=2048&q=20'>
  <Heading
    f={[ 4, 5, 6, 7 ]}>
    Hello
  </Heading>
</Banner>
```

Extends: [Flex](/components/Flex) > [Box](/components/Box)

prop | default | theme key | style type
---|---|---|---
flexDirection | column | N/A | responsive
alignItems | center | N/A | responsive
justifyContent | center | N/A | responsive
backgroundSize | cover | N/A | default
backgroundPosition | center | N/A | default
minHeight | 80vh | minHeights | responsive
backgroundImage |  | N/A | default