# Awesome-Shelf-Intelligence-Platform

## Top Shelf Intelligence Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Retail Shelf Monitoring, Planogram Compliance, Out-of-Stock Detection, Share of Shelf & Computer Vision for CPG/Retail Execution*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Shelf Intelligence**. These systems use computer vision and AI to analyze shelf images or camera feeds, measure planogram compliance, detect out-of-stocks, calculate share of shelf, and improve retail execution for brands and retailers.

**Examples** include Trax Retail, ParallelDots ShelfWatch, Scandit ShelfView, Teamcore, Focal Systems, Planorama, Perfect Store, Retail Insight, Simbe Robotics, and Caper AI (the category leaders).

**Open-source emphasis**: Production-grade, multi-retailer shelf intelligence platforms with large trained models and field workflows remain commercial. Open-source activity is strong in research and proof-of-concept systems built on YOLO, embeddings, and public datasets (SKU-110K, etc.). **Retail-Shelf-Monitoring**, **StoreEye**, academic pipelines, and related computer-vision projects provide useful starting points. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Trax Retail](https://traxretail.com/)**  
  Leading global retail execution and image-recognition platform used by major CPG companies and retailers for shelf analytics, planogram compliance, out-of-stock detection, and share-of-shelf measurement.

- **[ParallelDots ShelfWatch](https://www.paralleldots.com/)**  
  AI-powered shelf monitoring and retail execution platform focused on turning shelf images into actionable compliance and availability data.

- **[Scandit ShelfView / computer vision](https://www.scandit.com/)**  
  Mobile computer-vision SDK and shelf analytics capabilities that enable barcode, text, and shelf-scene understanding in field applications.

- **[Focal Systems](https://focal.systems/)**  
  AI shelf-camera platform that continuously monitors on-shelf availability, planogram compliance, and out-of-stocks in grocery and retail stores.

- **[Planorama, Teamcore, Perfect Store](https://www.planorama.com/)**  
  Specialized retail execution and shelf-intelligence solutions serving regional and vertical markets with image recognition and field workflows.

- **[Simbe Robotics](https://www.simberobotics.com/)**  
  Autonomous inventory robots that scan store shelves to provide real-time stock and planogram insights.

- **[Caper AI and related checkout/vision platforms](https://www.caper.ai/)**  
  Computer-vision systems originally focused on autonomous checkout that also contribute to product recognition and shelf understanding.

- **[Other retail execution & shelf analytics platforms](https://traxretail.com/)**  
  Additional vendors offering image recognition, field audit tools, and digital shelf / e-commerce monitoring capabilities.

## Open-Source GitHub Projects

- **[Retail-Shelf-Monitoring](https://github.com/Alijanloo/Retail-Shelf-Monitoring)**  
  Real-time retail shelf monitoring system using computer vision and machine learning to detect out-of-stocks, misplaced items, and support planogram compliance analysis.

- **[StoreEye](https://github.com/ALL-FOR-ONE-TECH/StoreEye-Enterprise-API-AI-Pipeline)**  
  Open-source, brand-agnostic FMCG shelf intelligence platform aimed at shelf visibility, planogram compliance, and competitive share-of-shelf analytics.

- **[Shelf Management (academic pipeline)](https://github.com/rokopi-byte/shelf_management)**  
  Deep-learning codebase and dataset accompanying research on shelf visual monitoring, product recognition, and planogram-related tasks.

- **[cvpce – Planogram Compliance Evaluation](https://github.com/laitalaj/cvpce)**  
  Computer-vision toolkit focused on evaluating planogram compliance from shelf images (research/academic origin).

- **[YOLO + SKU-110K based detectors](https://github.com/search?q=SKU-110K+OR+shelf+detection+YOLO)**  
  Numerous open-source object-detection projects trained or fine-tuned on the popular SKU-110K retail shelf dataset for product localization.

- **[Embedding & recognition pipelines](https://github.com/search?q=shelf+product+recognition+OR+planogram+compliance+computer+vision)**  
  Projects that combine detection with image embeddings and similarity search for SKU identification.

- **[AWS / cloud guidance samples](https://github.com/aws-solutions-library-samples/guidance-for-managing-planograms-with-amazon-bedrock)**  
  Reference architectures and sample code for planogram generation and compliance checking using cloud AI services (useful patterns even if not pure open-source models).

- **[Other retail CV research code](https://github.com/search?q=retail+shelf+OR+planogram+OR+%22out+of+stock%22+detection)**  
  Academic and community repositories exploring shelf row detection, facing counts, and related retail computer-vision problems.

### Additional Strong Open-Source Options

- **Object detection frameworks**: YOLO family, Detectron2, and related models fine-tuned on retail imagery.
- **Feature extraction & retrieval**: CLIP-style or MobileNet embeddings + FAISS/Annoy for fast product matching.
- **Dataset resources**: Public shelf datasets (SKU-110K and derivatives) used to train and benchmark models.
- **Annotation tools**: Open-source labeling platforms that support shelf-image workflows.
- **Edge deployment**: TensorRT, TFLite, and ONNX runtimes for running shelf models on store hardware or mobile devices.
- Integration patterns that feed detections into retail execution or inventory systems.

**Frameworks for building custom systems**:  
For research, POCs, or internal tools, start with YOLO-based detection on SKU-110K-style data, then add embedding-based SKU recognition and simple planogram rules (as demonstrated in the open-source projects above).  
Production-scale accuracy across thousands of SKUs, multi-country retailer variation, continuous model improvement, and field-force workflows are the domain of commercial platforms (Trax, Focal Systems, ParallelDots, Scandit, Simbe, etc.).  
Most organizations that need reliable, audit-grade shelf intelligence still rely on commercial solutions while using open-source computer vision for experimentation and custom extensions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Shelf intelligence systems influence inventory decisions, retailer compliance scores, and commercial negotiations. Accuracy, bias across products/lighting conditions, and data privacy (store imagery) must be carefully managed.
- Open-source models and research code are valuable for learning and prototyping but typically lack the scale, robustness, and support required for large-scale commercial retail execution programs.

---

**Made for CPG brands, retailers, retail execution teams, computer-vision engineers, and store-operations leaders.**  
Let's advance open research and practical tools that improve on-shelf availability and retail execution transparency.
