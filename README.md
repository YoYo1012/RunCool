# RunCool
int coinCount = Random.Range(0, 1+1);
Score[] scores = clone.GetComponentsInChildren<Score>();//抓取小道具
for (int i = 0; i < coinCount; i++)
    {
        int index = Random.Range(0, scores.Length);
        scores[index].GetComponent<SpriteRenderer>().sprite = Wave;//將小道具換成超級道具
        scores[index].name = Wave.name;
    }
# 你好
