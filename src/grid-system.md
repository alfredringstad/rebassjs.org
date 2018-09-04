
export const name = 'Grid System'

# Grid System

Rebass includes the incredibly flexible, responsive flexbox grid system [Grid Styled][grid-styled].
Use the `<Flex />` and `<Box />` components to fine tune spacing and alignment in a variety of combination.

```.jsx
<Flex mx={-2}>
  <Box width={1/2} px={2}>
    <Text p={1} color='white' bg='blue'>
      Half
    </Text>
  </Box>
  <Box width={1/2} px={2}>
    <Text p={1} color='white' bg='blue'>
      Half
    </Text>
  </Box>
</Flex>
```

```.jsx
<Flex flexWrap='wrap' mx={-2}>
  <Box px={2} py={2} width={1/2}>
    <Text p={1} color='white' bg='blue'>
      1/2
    </Text>
  </Box>
  <Box px={2} py={2} width={1/2}>
    <Text p={1} color='white' bg='blue'>
      1/2
    </Text>
  </Box>
  <Box px={2} py={2} width={1/3}>
    <Text p={1} color='white' bg='blue'>
      1/3
    </Text>
  </Box>
  <Box px={2} py={2} width={1/3}>
    <Text p={1} color='white' bg='blue'>
      1/3
    </Text>
  </Box>
  <Box px={2} py={2} width={1/3}>
    <Text p={1} color='white' bg='blue'>
      1/3
    </Text>
  </Box>
  <Box px={2} py={2} width={1/4}>
    <Text p={1} color='white' bg='blue'>
      1/4
    </Text>
  </Box>
  <Box px={2} py={2} width={1/4}>
    <Text p={1} color='white' bg='blue'>
      1/4
    </Text>
  </Box>
  <Box px={2} py={2} width={1/4}>
    <Text p={1} color='white' bg='blue'>
      1/4
    </Text>
  </Box>
  <Box px={2} py={2} width={1/4}>
    <Text p={1} color='white' bg='blue'>
      1/4
    </Text>
  </Box>
</Flex>
```

```.jsx
<Flex alignItems='center'>
  <Box width={1/3}>
    <Heading
      py={4}
      fontSize={[ 5, 6 ]}
      color='white'
      bg='blue'>
      Hello
    </Heading>
  </Box>
  <Box width={1/3} ml='auto'>
    <Text>Grid</Text>
  </Box>
</Flex>
```

See the [Grid Styled documentation][grid-styled] for more.

[grid-styled]: https://github.com/jxnblk/grid-styled
