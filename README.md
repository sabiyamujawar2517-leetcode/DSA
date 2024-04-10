# DSA
DSA Practice Questions
## Arrays
LeetCode Two Sum array Dry Run 
	  Dictionary empty == 
	 for(int i = 0; i < nums.Length; i++)
        {
            if(check.ContainsKey(target - nums[i]))
            {
                return new int[]{check[target-nums[i]], i3};
            }
            check[nums[i]] = i;
        }
		
i ==> 0 9 - 11 = -2
	Check[11] = 0;
	9-15 =-6
i ==> 1 	Check[15] = 1;
	9- 7 = 2
i ==> 2 	Check [7] = 2;
	 9 - 2 = 7
i ==> 3	  
	Check[9-2],3
	int[]{Check[7],3}
		 return {2,3}
