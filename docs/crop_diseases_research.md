# Crop Disease Research - AgriSense

## Overview
This document lists the major crops in India and their common diseases that AgriSense will detect.

## Target Crops (8 crops for MVP)

### 1. Rice (India's #1 crop)
| Disease | Type | Symptoms | Affected Areas |
|---------|------|----------|----------------|
| Rice Blast | Fungal | Grey lesions with dark borders | Panicles, leaves, nodes |
| Brown Spot | Fungal | Small brown circular spots | Leaves, grains |
| Sheath Blight | Fungal | Water-soaked lesions on leaf sheath | Sheath, leaves |
| Bacterial Leaf Blight | Bacterial | Yellow-white streaks along veins | Leaves |

### 2. Wheat
| Disease | Type | Symptoms |
|---------|------|----------|
| Yellow Rust (Stripe Rust) | Fungal | Yellow pustules in stripes |
| Brown Rust (Leaf Rust) | Fungal | Brown pustules scattered |
| Black Rust (Stem Rust) | Fungal | Black pustules on stems |
| Powdery Mildew | Fungal | White powdery growth on leaves |

### 3. Tomato
| Disease | Type | Symptoms |
|---------|------|----------|
| Late Blight | Fungal | Dark spots, white mold underside |
| Early Blight | Fungal | Concentric rings on leaves |
| Leaf Mold | Fungal | Yellow spots, purple mold |
| Tomato Yellow Leaf Curl | Viral | Curled yellow leaves, stunted growth |

### 4. Potato
| Disease | Type | Symptoms |
|---------|------|----------|
| Late Blight | Fungal | Dark lesions, white mold |
| Early Blight | Fungal | Dark concentric lesions |
| Potato Virus Y | Viral | Mottled leaves, reduced yield |
| Blackleg | Bacterial | Black stem base, wilting |

### 5. Maize/Corn
| Disease | Type | Symptoms |
|---------|------|----------|
| Northern Leaf Blight | Fungal | Long cigar-shaped lesions |
| Southern Rust | Fungal | Small brown pustules |
| Gray Leaf Spot | Fungal | Rectangular gray lesions |
| Common Rust | Fungal | Circular brown pustules |

### 6. Cotton
| Disease | Type | Symptoms |
|---------|------|----------|
| Leaf Curl Virus | Viral | Curled, thickened leaves |
| Fusarium Wilt | Fungal | Yellowing, wilting, vascular discoloration |
| Bacterial Blight | Bacterial | Angular leaf spots |

### 7. Sugarcane
| Disease | Type | Symptoms |
|---------|------|----------|
| Red Rot | Fungal | Red internal tissue, drying |
| Smut | Fungal | Whip-like black structure |
| Yellow Leaf Virus | Viral | Yellowing leaves |

### 8. Chickpea (Bengal Gram)
| Disease | Type | Symptoms |
|---------|------|----------|
| Wilt | Fungal | Wilting, yellowing |
| Ascochyta Blight | Fungal | Circular spots on leaves and pods |

## Dataset Sources

| Source | Link | Images |
|--------|------|--------|
| PlantVillage | https://www.kaggle.com/datasets/emmarex/plantdisease | 50,000+ |
| PlantDoc | https://github.com/pratikkayal/PlantDoc-Dataset | 2,500+ |
| New Plant Diseases | https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset | 87,000+ |

## Target Diseases for MVP (15 diseases)

1. Rice Blast
2. Brown Spot (Rice)
3. Wheat Yellow Rust
4. Wheat Brown Rust
5. Tomato Late Blight
6. Tomato Early Blight
7. Potato Late Blight
8. Potato Early Blight
9. Maize Northern Leaf Blight
10. Maize Gray Leaf Spot
11. Cotton Leaf Curl Virus
12. Sugarcane Red Rot
13. Chickpea Wilt
14. Healthy Leaf (for each crop)
15. Unhealthy but unidentified (catch-all)

## Next Steps
- Download PlantVillage dataset
- Organize images by disease class
- Start data preprocessing
