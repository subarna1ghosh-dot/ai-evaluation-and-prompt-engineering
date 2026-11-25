# Case Study 2: Bengali AI Localization & Language Quality Review

## Source English Prompt
> "Your account verification is pending. Please upload a clear photo of your government-issued ID to complete the process within 24 hours."

## Raw AI Bengali Output (Needs Improvement)
> "আপনার অ্যাকাউন্ট যাচাইকরণ মুলতুবি আছে। ২৪ ঘন্টার মধ্যে প্রক্রিয়াটি সম্পূর্ণ করতে অনুগ্রহ করে আপনার সরকার-প্রদত্ত আইডির একটি পরিষ্কার ছবি আপলোড করুন।"

### Issues Identified
1. **Unnatural Literal Translation:** "যাচাইকরণ মুলতুবি আছে" sounds overly robotic for user interfaces.
2. **Awkward Phrasing:** "সরকার-প্রদত্ত আইডি" is a literal word-for-word translation rather than natural Bengali.
3. **Spelling Detail:** "ঘন্টার" uses dental ন+ট instead of the standard conjunct ণ্ট (`ঘণ্টার`).

## Revised Natural Bengali Output (Human-Verified)
> "আপনার অ্যাকাউন্ট ভেরিফিকেশন এখনো সম্পন্ন হয়নি। প্রক্রিয়াটি শেষ করতে অনুগ্রহ করে আগামী ২৪ ঘণ্টার মধ্যে আপনার সরকারি পরিচয়পত্রের (ID) একটি স্পষ্ট ছবি আপলোড করুন।"
