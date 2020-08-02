#学习笔记
学习进度有点慢 学习时间太少 只看完了第一周的第三课 发现笔记记的也很少



#做题
var moveZeroes = function(nums) {
    let j=0;
    for (let i =0; i<nums.length;i++){
        if(nums[i] !=0){
            if(i!=j){
                nums[j] = nums[i];
                nums[i] = 0;
            }
            j++
        }
    }
};

