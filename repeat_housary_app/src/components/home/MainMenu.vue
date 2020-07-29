<template>
	<div>
		<div class="select-sorah">
			<div class="lesson"><button class="gold-btn small-btn">+</button><h2>درس اليوم</h2></div>
			<div class="form">
					<table width="100%" style="direction: rtl;">
					<tr>
						<td colspan="2"><p>مراجعة سورة</p></td>
						<td style="width: 30px;"></td>
						<td><p>تكرار الآية</p></td>
						<td><p>تكرار الفقرة</p></td>
					</tr>
					<tr>
						<td colspan="2" class='relative'>
							<p class="select-form" tabindex="1" onfocus="displaySelectMenu('ayat')" onfocusout="unDisplaySelectMenu('ayat')">
								<span> سورة</span>
								<span><i class="fas fa-chevron-down"></i></span>
									</p>
									<div class="select-menu" id="ayat">
										<div>الفاتحه</div>
										<div>البقره</div>
										<div>آل عمران</div>
										<div>النساء</div>
										<div>الأنعام</div>
										<div>المائدة</div>
										</div>
							</td>
							<td></td>
							<td class='relative'>
								<p class="select-form" tabindex="1"  onfocus="displaySelectMenu('ayat-repeat')" onfocusout="unDisplaySelectMenu('ayat-repeat')">
								<span class="arrow-right"><i class="fas fa-chevron-down"></i></span>
								<span>1</span>
									<span class="arrow-left"><i class="fas fa-chevron-down"></i></span>
										</p>>
										<!--<div class="simple-select" id="ayat-repeat">
												<div>بدون تكرار</div>
												<div>1</div>
												<div>2</div>
												<div>3</div>
												<div>4</div>
												<div>5</div>
												<div>6</div>
												<div>7</div/>
											</div>-->
							</td>
							<td class='relative'>
							<p class="select-form" tabindex="1">
								<span class="arrow-right"><i class="fas fa-chevron-down"></i></span>
								<span>1</span>
									<span class="arrow-left"><i class="fas fa-chevron-down"></i></span>
														</p>
											<!-- <div class="simple-select" style="width: 95%" id="part-repeat">
												<div>بدون تكرار</div>
												<div>1</div>
												<div>2</div>
												<div>3</div>
												<div>4</div>
												<div>5</div>
												<div>6</div>
												<div>7</div>
												</div>-->
							</td>
						</tr>
						<tr>
						<td colspan="2"><p>رقم الآيات</p></td>
						<td></td>
						<td colspan="2"><p>الإنتظار بين التلاوات</p></td>
						</tr>
						<tr>
						<td>
							<p class="select-form" tabindex="1">
							<span class="arrow-right"><i class="fas fa-chevron-down"></i></span>
							<span>1</span>						 
								<span class="arrow-left"><i class="fas fa-chevron-down"></i></span>
							</p>
						</td>
						<td>
							<p class="select-form" tabindex="1">
							<span class="arrow-right"><i class="fas fa-chevron-down"></i></span>
							<span>2</span>						 
								<span class="arrow-left"><i class="fas fa-chevron-down"></i></span>
							</p>
						</td>
						<td></td>
						<td colspan="2" class='relative'>
							<p class="select-form" tabindex="1" onfocus="displaySelectMenu('time')" onfocusout="unDisplaySelectMenu('time')">
								<span><i class="fas fa-chevron-down"></i></span>
								<span>1</span>
									</p>
									<div class="simple-select" style="width: 95%" id="time">
										<div>بدون إنتظار</div>
										<div>نصف مدة التلاوة</div>
										<div>نفس مدة التلاوة</div>
										<div>مره ونصف مدة التلاوة</div>
										<div>ضعف مدة التلاوة</div>
									</div>
						</td>
						</tr>
					</table>
				</div>
				<div class="lesson"><button class="gold-btn large-btn">أبدأ</button></div>

		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style>

</style>