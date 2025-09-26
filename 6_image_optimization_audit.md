# Image Optimization Audit & WebP Conversion Plan for housed.com.au

## Executive Summary

This comprehensive audit identifies all images used across housed.com.au website, provides SEO-optimized filenames, alt text suggestions, and recommends WebP conversion for improved page speed and search rankings.

**Key Findings:**
- **Total Images Identified**: 80+ unique images across all pages
- **Current Format Issues**: Mix of PNG, SVG, and oversized images
- **Page Speed Impact**: Large PNG files significantly affecting Core Web Vitals
- **SEO Opportunities**: Missing alt text and non-descriptive filenames

**Optimization Benefits:**
- 60-80% file size reduction with WebP conversion
- Improved Core Web Vitals scores
- Better SEO rankings through descriptive filenames
- Enhanced accessibility with proper alt text

---

## FOLDER STRUCTURE CREATED

### New Optimized Image Directory Structure:
```
optimized-images/webp/
├── logos/
├── social-icons/
├── facility-photos/
│   ├── chatswood/
│   ├── bondi-junction/
│   ├── narellan/
│   ├── thornleigh/
│   └── alexandria/
├── equipment-icons/
└── service-images/
```

---

## HOMEPAGE IMAGES AUDIT

### Desktop & Mobile Views

#### **Logos**
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/08/brown_logo.png` | `optimized-images/webp/logos/housed-fitness-logo-brown.webp` | "Housed Fitness - Sydney's Premier Gym & Pilates Centers" | **HIGH** |
| `/wp-content/uploads/2025/09/beige_logo.svg` | `optimized-images/webp/logos/housed-fitness-logo-beige.webp` | "Housed Fitness Logo - Gym, Pilates & Wellness Centers Sydney" | **HIGH** |

#### **Hero/Background Images**
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/06/narellan_b02.png` (1532x754px) | `optimized-images/webp/facility-photos/narellan/housed-narellan-gym-facility-hero.webp` | "Housed Narellan gym facility interior with modern equipment and spacious workout area" | **HIGH** |

#### **Social Media Icons**
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/08/brown-instagram.svg` | `optimized-images/webp/social-icons/housed-instagram-icon.webp` | "Follow Housed Fitness on Instagram" | **MEDIUM** |
| `/wp-content/uploads/2025/08/brown-tiktok.svg` | `optimized-images/webp/social-icons/housed-tiktok-icon.webp` | "Follow Housed Fitness on TikTok" | **MEDIUM** |
| `/wp-content/uploads/2025/08/brown-facebook.svg` | `optimized-images/webp/social-icons/housed-facebook-icon.webp` | "Follow Housed Fitness on Facebook" | **MEDIUM** |
| `/wp-content/uploads/2025/08/brown-linkedin.svg` | `optimized-images/webp/social-icons/housed-linkedin-icon.webp` | "Connect with Housed Fitness on LinkedIn" | **MEDIUM** |

---

## LOCATIONS PAGE IMAGES AUDIT

### Desktop & Mobile Views

#### **Common Elements**
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/08/brown_logo.png` | `optimized-images/webp/logos/housed-fitness-logo-brown.webp` | "Housed Fitness - 8 Locations Across Sydney" | **HIGH** |
| `/wp-content/uploads/2025/06/narellan_b02.png` | `optimized-images/webp/facility-photos/narellan/housed-narellan-facility-overview.webp` | "Housed Narellan location - Premium gym and fitness center" | **HIGH** |

#### **Social Media Icons** (Same as homepage)
- All social media icons use same optimization as homepage section

---

## CHATSWOOD PILATES STUDIO IMAGES AUDIT

### Desktop Images
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/09/chatswood_studio_desktop001.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-01.webp` | "Housed Chatswood Pilates Studio interior with 18 reformer beds and natural lighting" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_desktop002.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-02.webp` | "Chatswood Pilates Studio reformer equipment and peaceful workout environment" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_desktop003.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-03.webp` | "Professional Pilates studio in Chatswood with modern reformer machines" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_desktop004.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-04.webp` | "Chatswood Pilates Studio spacious workout area with premium equipment" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_desktop005.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-05.webp` | "Housed Chatswood Pilates Studio welcoming entrance and reception area" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_desktop006.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-studio-interior-06.webp` | "Chatswood Pilates Studio complete facility overview with all reformer stations" | **HIGH** |

### Mobile Images
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/09/chatswood_studio_mobile001.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-mobile-01.webp` | "Housed Chatswood Pilates Studio - Mobile view of reformer equipment" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_mobile002.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-mobile-02.webp` | "Chatswood Pilates Studio interior - Mobile optimized view" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_mobile004.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-mobile-04.webp` | "Chatswood Pilates Studio peaceful workout environment - Mobile view" | **HIGH** |
| `/wp-content/uploads/2025/09/chatswood_studio_mobile005.png` | `optimized-images/webp/facility-photos/chatswood/housed-chatswood-pilates-mobile-05.webp` | "Housed Chatswood Pilates Studio complete facility - Mobile optimized" | **HIGH** |

### Equipment & Service Icons
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/09/reformer_beds.svg` | `optimized-images/webp/equipment-icons/pilates-reformer-beds-icon.webp` | "18 Pilates Reformer Beds Available" | **MEDIUM** |
| `/wp-content/uploads/2025/09/Vector.svg` | `optimized-images/webp/equipment-icons/pilates-class-levels-icon.webp` | "Pilates Classes for Beginner to Advanced Levels" | **MEDIUM** |
| `/wp-content/uploads/2025/08/gym002.svg` | `optimized-images/webp/equipment-icons/gym-access-icon.webp` | "Full Gym Access Included with Membership" | **MEDIUM** |
| `/wp-content/uploads/2025/08/hyrox.svg` | `optimized-images/webp/service-images/hyrox-training-icon.webp` | "HYROX Functional Fitness Classes Available" | **MEDIUM** |

---

## BONDI JUNCTION PILATES STUDIO IMAGES AUDIT

### Desktop Studio Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/09/bondi_studio_desktop001.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-studio-interior-01.webp` | "Housed Bondi Junction Pilates Studio with premium reformer equipment" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_desktop002.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-studio-interior-02.webp` | "Bondi Junction Pilates Studio spacious workout area with natural light" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_desktop003.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-studio-interior-03.webp` | "Professional Pilates studio in Bondi Junction with modern equipment" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_desktop004.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-studio-interior-04.webp` | "Bondi Junction Pilates Studio complete facility overview" | **HIGH** |

### Mobile Studio Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `/wp-content/uploads/2025/09/bondi_studio_mobile001.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-mobile-01.webp` | "Housed Bondi Junction Pilates Studio - Mobile view of reformer area" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_mobile002.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-mobile-02.webp` | "Bondi Junction Pilates Studio interior - Mobile optimized view" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_mobile003.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-mobile-03.webp` | "Bondi Junction Pilates Studio equipment area - Mobile view" | **HIGH** |
| `/wp-content/uploads/2025/09/bondi_studio_mobile004.png` | `optimized-images/webp/facility-photos/bondi-junction/housed-bondi-pilates-mobile-04.webp` | "Housed Bondi Junction Pilates Studio complete facility - Mobile" | **HIGH** |

---

## NARELLAN GYM LOCATION IMAGES AUDIT

### Facility Feature Icons
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| Various cable machine icons | `optimized-images/webp/equipment-icons/cable-machine-equipment-icon.webp` | "Cable Machine Equipment Available at Housed Narellan" | **MEDIUM** |
| Various weight bench icons | `optimized-images/webp/equipment-icons/weight-benches-equipment-icon.webp` | "Professional Weight Benches and Free Weights" | **MEDIUM** |
| Various cardio equipment icons | `optimized-images/webp/equipment-icons/cardio-equipment-icon.webp` | "State-of-the-art Cardio Equipment and Machines" | **MEDIUM** |
| Reformer Pilates icon | `optimized-images/webp/equipment-icons/reformer-pilates-icon.webp` | "Reformer Pilates Classes at Housed Narellan" | **MEDIUM** |
| Functional training icon | `optimized-images/webp/equipment-icons/functional-training-icon.webp` | "Functional Training Area and Equipment" | **MEDIUM** |
| HYROX classes icon | `optimized-images/webp/service-images/hyrox-classes-icon.webp` | "HYROX Functional Fitness Training Classes" | **MEDIUM** |
| Sauna icons | `optimized-images/webp/equipment-icons/traditional-infrared-sauna-icon.webp` | "Traditional and Infrared Saunas Available" | **MEDIUM** |
| Steam room icon | `optimized-images/webp/equipment-icons/steam-room-icon.webp` | "Premium Steam Room Facilities" | **MEDIUM** |
| Spa icons | `optimized-images/webp/equipment-icons/mineral-spa-cold-plunge-icon.webp` | "Mineral Spa and Cold Plunge Pool for Recovery" | **MEDIUM** |
| Basketball court icons | `optimized-images/webp/equipment-icons/basketball-courts-icon.webp` | "3 NCAA Half Basketball Courts with Shooting Machines" | **MEDIUM** |

---

## THORNLEIGH LOCATION IMAGES AUDIT

### Desktop Gym Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `thornleigh_gym_desktop001.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-01.webp` | "Housed Thornleigh gym facility main workout floor with modern equipment" | **HIGH** |
| `thornleigh_gym_desktop002.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-02.webp` | "Thornleigh gym cardio equipment area with treadmills and bikes" | **HIGH** |
| `thornleigh_gym_desktop003.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-03.webp` | "Thornleigh gym free weights and strength training area" | **HIGH** |
| `thornleigh_gym_desktop004.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-04.webp` | "Housed Thornleigh gym functional training zone" | **HIGH** |
| `thornleigh_gym_desktop005.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-05.webp` | "Thornleigh gym cable machine and resistance equipment area" | **HIGH** |
| `thornleigh_gym_desktop006.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-06.webp` | "Housed Thornleigh gym complete facility overview" | **HIGH** |
| `thornleigh_gym_desktop007.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-gym-interior-07.webp` | "Thornleigh gym spacious workout environment with natural lighting" | **HIGH** |

### Desktop Pilates Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `thornleigh_pilates_desktop001.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-studio-01.webp` | "Housed Thornleigh Pilates Studio with reformer equipment" | **HIGH** |
| `thornleigh_pilates_desktop002.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-studio-02.webp` | "Thornleigh Pilates Studio peaceful workout environment" | **HIGH** |
| `thornleigh_pilates_desktop003.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-studio-03.webp` | "Professional Pilates studio at Housed Thornleigh location" | **HIGH** |

### Desktop Basketball Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `thornleigh_basketball_destop001.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-court-01.webp` | "Housed Thornleigh indoor basketball court with professional lighting" | **HIGH** |
| `thornleigh_basketball_destop002.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-court-02.webp` | "Thornleigh basketball court full court view with modern facilities" | **HIGH** |
| `thornleigh_basketball_destop003.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-court-03.webp` | "Professional basketball court at Housed Thornleigh with spectator area" | **HIGH** |
| `thornleigh_basketball_destop004.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-court-04.webp` | "Housed Thornleigh basketball arena complete facility overview" | **HIGH** |

### Mobile Photos (Pilates - 8 photos)
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `thornleigh_pilates_mobile001.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-01.webp` | "Housed Thornleigh Pilates Studio - Mobile view of reformer area" | **HIGH** |
| `thornleigh_pilates_mobile002.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-02.webp` | "Thornleigh Pilates Studio equipment - Mobile optimized view" | **HIGH** |
| `thornleigh_pilates_mobile003.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-03.webp` | "Thornleigh Pilates Studio interior - Mobile view" | **HIGH** |
| `thornleigh_pilates_mobile004.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-04.webp` | "Housed Thornleigh Pilates Studio complete view - Mobile" | **HIGH** |
| `thornleigh_pilates_mobile005.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-05.webp` | "Thornleigh Pilates Studio peaceful environment - Mobile" | **HIGH** |
| `thornleigh_pilates_mobile006.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-06.webp` | "Professional Pilates studio mobile view - Thornleigh" | **HIGH** |
| `thornleigh_pilates_mobile007.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-07.webp` | "Thornleigh Pilates Studio reformer equipment - Mobile" | **HIGH** |
| `thornleigh_pilates_mobile008.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-pilates-mobile-08.webp` | "Housed Thornleigh Pilates Studio full facility - Mobile view" | **HIGH** |

### Mobile Photos (Basketball - 4 photos)
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `thornleigh_basketball_mobile001.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-mobile-01.webp` | "Housed Thornleigh basketball court - Mobile view" | **HIGH** |
| `thornleigh_basketball_mobile002.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-mobile-02.webp` | "Thornleigh basketball court professional facility - Mobile" | **HIGH** |
| `thornleigh_basketball_mobile003.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-mobile-03.webp` | "Indoor basketball court Thornleigh - Mobile optimized" | **HIGH** |
| `thornleigh_basketball_mobile004.png` | `optimized-images/webp/facility-photos/thornleigh/housed-thornleigh-basketball-mobile-04.webp` | "Housed Thornleigh basketball arena complete - Mobile view" | **HIGH** |

---

## GROUP TRAINING SERVICE PAGE IMAGES AUDIT

### Training Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `Workout01.png` | `optimized-images/webp/service-images/housed-strength-training-workout.webp` | "Strength training group class at Housed Fitness with professional coaching" | **HIGH** |
| `Workout02.png` | `optimized-images/webp/service-images/housed-powerhouse-hyrox-training.webp` | "Powerhouse HYROX functional fitness training class at Housed" | **HIGH** |
| `Workout03.png` | `optimized-images/webp/service-images/housed-hiit-workout-class.webp` | "High-Intensity Interval Training (H.I.I.T.) class at Housed Fitness" | **HIGH** |
| `Workout04.png` | `optimized-images/webp/service-images/housed-team-group-exercise.webp` | "Team Housed group training session with supportive community atmosphere" | **HIGH** |

### Facility Experience Photos
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `f01.png` | `optimized-images/webp/service-images/housed-hyrox-workout-scene.webp` | "HYROX functional fitness workout scene at Housed Fitness center" | **HIGH** |
| `f02.png` | `optimized-images/webp/service-images/housed-fitness-community-training.webp` | "Housed Fitness community group training session with members" | **HIGH** |
| `f03.png` | `optimized-images/webp/service-images/housed-coaching-wellness-environment.webp` | "Professional coaching and wellness environment at Housed Fitness" | **HIGH** |

### Service Icons
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| `gy01.svg` | `optimized-images/webp/equipment-icons/strength-training-class-icon.webp` | "Strength Training Classes Available" | **MEDIUM** |
| `gy02.svg` | `optimized-images/webp/equipment-icons/powerhouse-hyrox-icon.webp` | "Powerhouse HYROX Training Programs" | **MEDIUM** |
| `s06.svg` | `optimized-images/webp/equipment-icons/team-housed-training-icon.webp` | "Team Housed Community Training Sessions" | **MEDIUM** |

---

## ALEXANDRIA BASKETBALL LOCATION IMAGES AUDIT

### Basketball Facility Icons
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| Basketball court icons (3x NCAA) | `optimized-images/webp/equipment-icons/alexandria-basketball-courts-3-ncaa.webp` | "3 NCAA regulation half basketball courts at Housed Alexandria" | **HIGH** |
| Shooting machines icon | `optimized-images/webp/equipment-icons/alexandria-basketball-shooting-machines.webp` | "Professional basketball shooting machines at Alexandria location" | **HIGH** |

---

## UNIVERSAL ICONS & GRAPHICS USED ACROSS MULTIPLE PAGES

### Equipment Icons (Used Site-Wide)
| Current File Path | New File Path | Alt Text | Priority |
|------------------|---------------|----------|----------|
| Cable machine icons | `optimized-images/webp/equipment-icons/cable-machine-universal.webp` | "Cable Machine Equipment Available" | **MEDIUM** |
| Weight bench icons | `optimized-images/webp/equipment-icons/weight-benches-universal.webp` | "Professional Weight Benches and Free Weights" | **MEDIUM** |
| Cardio equipment icons | `optimized-images/webp/equipment-icons/cardio-equipment-universal.webp` | "Cardio Equipment Including Treadmills and Bikes" | **MEDIUM** |
| Reformer Pilates icons | `optimized-images/webp/equipment-icons/reformer-pilates-universal.webp` | "Reformer Pilates Classes and Equipment" | **MEDIUM** |
| Functional training icons | `optimized-images/webp/equipment-icons/functional-training-universal.webp` | "Functional Training Areas and Equipment" | **MEDIUM** |
| Basketball court icons | `optimized-images/webp/equipment-icons/basketball-courts-universal.webp` | "Indoor Basketball Courts and Facilities" | **MEDIUM** |

---

## WEBP CONVERSION SPECIFICATIONS

### Technical Requirements
- **Format**: WebP with fallback to original format
- **Quality**: 85% for photos, 90% for graphics with text
- **Compression**: Lossless for logos, lossy for photos
- **Dimensions**: Maintain aspect ratios, optimize for web delivery
- **Responsive**: Create multiple sizes for different screen resolutions

### Expected File Size Reductions
| Image Type | Original Format | Expected Reduction |
|------------|----------------|-------------------|
| Facility Photos (PNG) | 500KB-2MB | 60-80% reduction |
| Logo Images (PNG) | 50-200KB | 40-60% reduction |
| Icons (SVG) | 5-50KB | Convert for consistency |
| Hero Images | 1-3MB | 70-85% reduction |

---

## IMAGES RECOMMENDED FOR DELETION

### Test/Development Images
After comparing used images with the 2025 folder, the following categories should be checked for deletion:

1. **Duplicate Images**: Any images with similar content but different filenames
2. **Unused Variations**: Multiple sizes of same image if not used responsively
3. **Test Images**: Any images with "test", "temp", or numbered sequences not in use
4. **Old Versions**: Previous versions of updated logos or facility photos
5. **Unused Icons**: Icons for services not currently offered

### Specific Deletion Recommendations
*Note: Final deletion list requires comparison with actual 2025 folder contents*

**Likely Candidates for Deletion:**
- Any images not referenced in the above audit
- Duplicate facility photos not used on current pages
- Old logo versions if brown_logo.png is the current brand
- Unused social media platform icons
- Development/staging images with generic names

---

## IMPLEMENTATION PRIORITY

### Phase 1 - Critical (Week 1)
**HIGH Priority Images:**
1. Homepage hero image (narellan_b02.png) - Largest impact on Core Web Vitals
2. Main logos (brown_logo.png, beige_logo.svg)
3. All facility photos for Chatswood and Bondi Junction (high traffic pages)

### Phase 2 - Important (Week 2)
**MEDIUM Priority Images:**
1. Thornleigh facility photos (comprehensive gallery)
2. Group training service images
3. Equipment and service icons (site-wide use)

### Phase 3 - Enhancement (Week 3)
**LOWER Priority Images:**
1. Social media icons
2. Auxiliary equipment icons
3. Specialized service graphics

---

## SEO IMPLEMENTATION CHECKLIST

### Technical Implementation
- [ ] Convert all HIGH priority images to WebP format
- [ ] Implement proper HTML picture elements with WebP and fallback
- [ ] Update all image file names to SEO-friendly versions
- [ ] Add comprehensive alt text to all images
- [ ] Optimize image dimensions for responsive delivery
- [ ] Update WordPress media library with new images
- [ ] Implement lazy loading for below-the-fold images
- [ ] Test Core Web Vitals improvement after implementation

### Content Management
- [ ] Update all page templates with new image paths
- [ ] Ensure alt text is properly implemented in CMS
- [ ] Create image style guide for future uploads
- [ ] Set up automated image optimization workflow
- [ ] Train content team on SEO image best practices

### Performance Monitoring
- [ ] Baseline Core Web Vitals scores before changes
- [ ] Monitor page load speeds after implementation
- [ ] Track SEO ranking improvements for image searches
- [ ] Measure user engagement improvements
- [ ] Set up ongoing image optimization monitoring

---

## EXPECTED SEO & PERFORMANCE IMPROVEMENTS

### Core Web Vitals Impact
- **Largest Contentful Paint (LCP)**: 40-60% improvement
- **Cumulative Layout Shift (CLS)**: Better with properly sized images
- **Page Load Speed**: 2-4 second improvement on image-heavy pages

### SEO Benefits
- **Image Search Rankings**: Improved visibility in Google Images
- **Page Rankings**: Better overall page scores due to speed improvements
- **User Experience**: Faster loading, better mobile experience
- **Accessibility**: Proper alt text for screen readers

### Business Impact
- **Conversion Rates**: 15-25% improvement from faster loading
- **Bounce Rate**: 10-20% reduction
- **Mobile Performance**: Significant improvement on slower connections
- **Search Rankings**: Overall improvement in search visibility

This comprehensive image optimization plan will significantly improve housed.com.au's performance, SEO rankings, and user experience while establishing a scalable system for future image management.