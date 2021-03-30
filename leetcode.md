1) Perform inorder traversal and check that each node is greater than the previous // 
2) Does not work if equal nodes are allowed // 
3) Time: O(n) Space : O(n) logn 
4) if balanced class TreeNode(object): self.val = x self.left = None self.right = None 
5) class Solution(object): def isValidBST(self,root): self.correct = True self.prev = float('-inf') self.inorder(root) return self.correct def inOrder(self,node): if not node or not self.correct : return if node.val <= self.prev: self.correct = False return 
6) Halt exploration self.prev = node.val self.inOrder(node.right)
