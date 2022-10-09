int cmp(const void *a, const void *b){
    return *(int*)a < *(int*)b;
}
int largestPerimeter(int* nums, int numsSize){
    qsort(nums, numsSize, sizeof(int), cmp);
    for(int i = 0; i < numsSize - 2; i++){
        if(nums[i] < nums[i + 1] + nums[i + 2])
            return nums[i] + nums[i + 1] + nums[i + 2];
        }return 0;
    }
           
