# -Integrate-LLMs-with-applications-

curl "https://us-south.ml.cloud.ibm.com/ml/v1/text/generation?version=2023-05-29" \
  -H 'Content-Type: application/json' \
  -H 'Accept: application/json' \
  -H "Authorization: Bearer ${YOUR_ACCESS_TOKEN}" \
  -d '{
	"input": "Please provide top 5 bullet points in the review provided in '\'''\'''\''.\n\n\nReview:\n'\'''\'''\''I had 2 problems with my experience with my refinance. 1) The appraisal company used only tried to lower my house value to fit the comps that he was able to find in the area. My house is unique and he did not use the unique pictures to compare value. He purposely left them out of the appraisal. 2) I started my loan process on a Thursday. On Saturday I tried to contact my loan officer to tell him of the American Express offer that I wanted to apply for. I was informed that it was too late and I could not use it because it would delay the process. I had just received the email about the offer and I had just started the process so how was it too late to get in on the $2,000 credit on my current bill. I let it go but I should have dropped the process and restarted it because that would have helped me out with my bill.'\'''\'''\''\n\nTop bullet points:\n1. The appraisal company undervalued the reviewer'\''s house by purposely excluding unique pictures that would have accurately assessed its value.\n2. The uniqueness of the house was not taken into consideration, and the appraiser relied solely on comps that did not reflect its true worth.\n3. The reviewer attempted to inform their loan officer about an American Express offer they wanted to apply for, which would have provided a $2,000 credit on their current bill.\n4. The loan officer stated it was too late to take advantage of the offer as it would delay the process, despite the reviewer having just received the email and recently started the loan process.\n5. The reviewer regrets not dropping the process and restarting it to benefit from the offer, as it would have helped them with their bill.\n\n\nReview:'\'''\'''\''\nFor the most part my experience was very quick and very easy. I did however, have 3 issues.\n\n#1 - When I received my final numbers, my costs were over $2000 more than was quoted to me over the phone. This was straightened out quickly and matched what I was quoted.\n\n#2 - The appraiser had to change his schedule and when I didn'\''t know if I could be home for the appraisal, he said he could do it with me not there. I do not think this is a wise thing to do or to offer.\n\n#3 - When I received my appraisal, it was far lower than it should have been. My house appraised for basically the same price I purchased it for 14 years ago. I have kept the home up with flooring, paint, etc. It has new shingles on it from last summer, the driveway has been paved, I have about three acres landscaped compared to maybe one when I bought it, and have paved the driveway which was originally gravel.\n\nEven if you discount the insanely high prices that houses are selling for in today'\''s market, the house has increased in value over the past fourteen years. In fact, some of the compared properties looked like camps that were not on water, had no basement or possibly no slab, and very minimal acreage. These comparably priced houses were in no way equal to my 4 bedroom cape, with a wraparound deck, on 4 acres, though not on the water, it is overlooking lake around 100 feet away at the most. I feel very strongly that the appraisal price was put in at a high enough estimate to satisfy the needs of the refinance loan.'\'''\'''\''\n\nTop bullet points:\n1. Overall, the experience was quick and easy, but there were three specific issues.\n2. Initially, the quoted costs over the phone did not match the final numbers, resulting in a discrepancy of over $2000. However, this was promptly resolved.\n3. The appraiser offered to conduct the appraisal without the homeowner present, which the reviewer felt was unwise and not recommended.\n4. The appraisal value of the house was significantly lower than expected, even considering the current high housing market prices. The reviewer mentioned various upgrades and improvements made to the house over the past 14 years.\n5. The reviewer expressed a strong belief that the appraisal was deliberately set at a lower value to meet the requirements of the refinance loan, despite the property'\''s unique features and advantages compared to the comparables used.\n\n\nReview:'\'''\'''\''\nI was told upfront and throughout most of the process that I would be able to get a $25K payout/cash back based on the market value of my house that was discussed in the original conversation with the loan officer. However, midway into the process I was told by the loan officer that I was only able to get $17.5K back. Additionally, I was told that I would be able to skip 2 months of mortgage payment to help makeup for the cash shortage. However, at the end of the day I was told that I could only skip 1 mortgage payment. These 2 drawbacks caused me to not fully satisfy the financial reason of why I originally wanted to refinance which was to get the $25K cash.\n\nTop bullet points:\n1. The initial agreement with the loan officer stated that the reviewer would receive a $25K cash payout based on the market value of their house.\n2. Midway through the process, the loan officer informed the reviewer that they would only be eligible for a $17.5K cash payout, which was lower than initially discussed.\n3. The reviewer was also promised the ability to skip two months of mortgage payments to compensate for the cash shortage, but they were later informed that they could only skip one payment.\n4. These discrepancies in the cash payout amount and the reduced mortgage payment relief prevented the reviewer from fulfilling their original financial objective of obtaining the $25K cash.\n5. The limitations and changes in the terms impacted the overall satisfaction with the refinancing process and compromised the financial benefits the reviewer had anticipated.\n\nReview:'\'''\'''\''\nI started my loan process toward securing a VA loan. I was waiting for a a month and a couple weeks, then I was told that the VA needed to acquire my retirement points to verify my veteran status. If I knew this is what my loan was on hold for, I could have contacted the VA office right away and got this cleared up. \nFor whatever reason, it took the underwriting department a long time to verify my employment status, even after I uploaded a couple years of my W2 forms from both of my jobs, and they had my Social Security number to further verify my employment status. My loan completion date was extended, because I wasn'\''t made aware that they were waiting for my VA status to be approved. The push back for my mortgage is common for mortgage companies, but this caused my interest rate to go up. Then, the securing of a closing lawyer being made aware to me and the lawyer needing three days to get their end prepared for me to go to their office to sign the paperwork wasn'\''t made aware to me. My loan missed the second closing date. For whatever reason, the locked in interest rate jumped up 5/8 points. After making the banker I was working with aware of this, he didn'\''t understand why the locked in interest rate jumped up either. He was nice enough to work on it and was able to get the interest rate down in 1/4 of a point, so my mortgage has an interest rate that is 3/8 of a point higher than my locked in interest rate in the beginning of this process. Although my interest rate is higher than the locked in interest point, at the end, the mortgage is successfully finished.\n'\'''\'''\''\n\nTop bullet points:1. The VA needed to acquire my retirement points to verify my veteran status. 2. The underwriting department took a long time to verify my employment status. 3. The push back for my mortgage is common for mortgage companies, but this caused my interest rate to go up. 4. The securing of a closing lawyer being made aware to me and the lawyer needing three days to get their end prepared for me to go to their office to sign the paperwork wasn'\''t made aware to me. 5. For whatever reason, the locked in interest rate jumped up 5/8 points.",
	"parameters": {
		"decoding_method": "greedy",
		"max_new_tokens": 300,
		"min_new_tokens": 50,
		"stop_sequences": [],
		"repetition_penalty": 1
	},
	"model_id": "google/flan-ul2",
	"project_id": "90f555f3-ed2e-4c2e-86fb-78426efa7e23",
	"moderations": {
		"hap": {
			"input": {
				"enabled": true,
				"threshold": 0.5,
				"mask": {
					"remove_entity_value": true
				}
			},
			"output": {
				"enabled": true,
				"threshold": 0.5,
				"mask": {
					"remove_entity_value": true
				}
			}
		},
		"pii": {
			"input": {
				"enabled": true,
				"threshold": 0.5,
				"mask": {
					"remove_entity_value": true
				}
			},
			"output": {
				"enabled": true,
				"threshold": 0.5,
				"mask": {
					"remove_entity_value": true
				}
			}
		}
	}
}'
