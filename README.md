# react-native-quikkly-refactored
** React Native Quikkly Module with scan single image **

-*Function name : scanSingleImage(option)*

-** Example **
```
QuikklyManager.scanSingleImage({ photoUri: response.uri }).then(
  (result) => {
	if (
	  result.startsWith('image') ||
	  result.startsWith('erro') ||
	  result.startsWith('invalid')
	) {
	  console.log('Quikkly Error');
	  console.log(result);
	} else {
	  console.log(result);
	}
  },
);
```
