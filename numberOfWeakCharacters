class Solution:
    def numberOfWeakCharacters(self, properties: List[List[int]]) -> int:
        count=0
        properties = sorted(properties, key = lambda x: (-x[0],x[1]))
        maxDefence = properties[0][1]
        for i in properties:
            if i[1]<maxDefence:
                count+=1
            maxDefence = max(i[1], maxDefence)
        return count
        
