import unittest
from EmotionDetection.emotion_detection import emotion_detector

class TestEmotionDetector(unittest.TestCase):
    def test_emotion_detector(self):
        # 1. Test case cho cảm xúc 'joy'
        result_1 = emotion_detector('I am glad this happened')
        self.assertEqual(result_1['dominant_emotion'], 'joy')
        
        # 2. Test case cho cảm xúc 'anger'
        result_2 = emotion_detector('I am really mad about this')
        self.assertEqual(result_2['dominant_emotion'], 'anger')
        
        # 3. Test case cho cảm xúc 'disgust'
        result_3 = emotion_detector('I feel disgusted just hearing about this')
        self.assertEqual(result_3['dominant_emotion'], 'disgust')
        
        # 4. Test case cho cảm xúc 'sadness'
        result_4 = emotion_detector('I am so sad about this')
        self.assertEqual(result_4['dominant_emotion'], 'sadness')
        
        # 5. Test case cho cảm xúc 'fear'
        result_5 = emotion_detector('I am really afraid that this will happen')
        self.assertEqual(result_5['dominant_emotion'], 'fear')

if __name__ == '__main__':
    unittest.main()