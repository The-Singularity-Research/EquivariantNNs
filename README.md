# EquivariantNNs

## Equivariant Bases for Coordinate Rings of Spaces of Linear Maps
Equivariant linear maps are fundamental to designing neural networks with equivariant layers. 
This repo will help in constructing the coordinate ring K[Hom(V,W)] = K[Mat(n,m)], of the space 
of linear maps between the vector spaces V and W, with Young tableaux as equivariant monomial 
basis. We have included several references for this construction that may be of help in the 
study of equivariant neural networks. 

There is a diality between the points (i.e. a single linear map) in the space of all linear maps, 
and the space of polynomial function on it. We denote points (linear maps or matrices) from the 
vector space $V \cong K^n$ to the vector space $W \cong K^m$, by 
$$\mathbf{Hom}_K(V,W) \cong \mathbf{Mat}_{m \times n}(K)$$. We denote the space of polynomial
functions on $$\mathbf{Hom}_K(V,W)$$ by $$K[\mathbf{Hom}_K(V,W)] \cong K[\mathbf{Mat}_{m \times n}(K)]$$

This duality implies it is helpful to understand how to find an equivariant basis of 
"*standard monomials*" for the "*coordinate ring*" $K[\mathbf{Hom}_K(V,W)]$ with respect to some
group action. In the references we provide, this group is $\mathbf{GL}(V) \times \mathbf{GL}(W)$. 
Using the theory of [Frobenius reciprocity](https://en.wikipedia.org/wiki/Frobenius_reciprocity) we can apply "*induction*" and "*restriction*" of 
representations to find equivariant bases with respect to other group actions of the form
$G_1 \times G_2$ where $G_1 \subset \mathbf{GL}(V)$ is a subgroups and likewise $G_2 \subset \mathbf{GL}(W)$.


