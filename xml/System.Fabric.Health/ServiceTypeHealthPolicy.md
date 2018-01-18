<Type Name="ServiceTypeHealthPolicy" FullName="System.Fabric.Health.ServiceTypeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ServiceTypeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceTypeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceTypeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceTypeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ServiceTypeHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="cf390-101">サービスの種類に属するサービスの正常性を評価するために使用する正常性ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="cf390-101">Represents the health policy used to evaluate the health of services belonging to a service type.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTypeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="cf390-102"><see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cf390-102">Initializes a new instance of <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="cf390-103">既定では、エラーまたは警告が許容されません。</span><span class="sxs-lookup"><span data-stu-id="cf390-103">By default, no errors or warnings are tolerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyPartitionsPerService">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyPartitionsPerService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyPartitionsPerService As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyPartitionsPerService : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cf390-104">取得またはサービスごとの問題のあるパーティションの最大許容パーセンテージを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf390-104">Gets or sets the maximum allowed percentage of unhealthy partitions per service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cf390-105">許容されるサービスごとの問題のあるパーティションの割合の最大値を返します。</span><span class="sxs-lookup"><span data-stu-id="cf390-105">Returns the maximum allowed percentage of unhealthy partitions per service.</span></span>
            <span data-ttu-id="cf390-106">使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</span><span class="sxs-lookup"><span data-stu-id="cf390-106">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="cf390-107">パーセンテージは、パーティションことのできる正常な状態、サービスがエラーと見なされるまでの最大許容パーセンテージを表します。</span><span class="sxs-lookup"><span data-stu-id="cf390-107">The percentage represents the maximum tolerated percentage of partitions that can be unhealthy before the service is considered in error.</span></span> <span data-ttu-id="cf390-108">割合が守られて異常な場合に、少なくとも 1 つのパーティションがある場合は、正常性は警告として評価されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-108">If the percentage is respected but there is at least one unhealthy partition, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="cf390-109">これは、サービスのパーティションの総数に対して異常なパーティションの数で割ることによって計算されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-109">This is calculated by dividing the number of unhealthy partitions over the total number of partitions in the service.</span></span>
            <span data-ttu-id="cf390-110">計算は、パーティション数が少ないで 1 つの障害を許容するように丸めます。</span><span class="sxs-lookup"><span data-stu-id="cf390-110">The computation rounds up to tolerate one failure on small numbers of partitions.</span></span> <span data-ttu-id="cf390-111">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="cf390-111">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="cf390-112">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="cf390-112">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cf390-113">取得または設定パーティションあたりの異常なレプリカの最大許容パーセンテージです。</span><span class="sxs-lookup"><span data-stu-id="cf390-113">Gets or sets the maximum allowed percentage of unhealthy replicas per partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cf390-114">許容される異常なレプリカ パーティションあたりの割合の最大値を返します。</span><span class="sxs-lookup"><span data-stu-id="cf390-114">Returns the maximum allowed percentage of unhealthy replicas per partition.</span></span>
            <span data-ttu-id="cf390-115">使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</span><span class="sxs-lookup"><span data-stu-id="cf390-115">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="cf390-116">パーセンテージは、ことのできる正常なエラーでは、パーティションは考慮する前にレプリカの最大許容パーセンテージを表します。</span><span class="sxs-lookup"><span data-stu-id="cf390-116">The percentage represents the maximum tolerated percentage of replicas that can be unhealthy before the partition is considered in error.</span></span> <span data-ttu-id="cf390-117">割合が守られて異常な場合に、少なくとも 1 つのレプリカがある場合は、正常性は警告として評価されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-117">If the percentage is respected but there is at least one unhealthy replica, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="cf390-118">これは、パーティション内のレプリカの合計数に問題があるレプリカの数で割ることによって計算されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-118">This is calculated by dividing the number of unhealthy replicas over the total number of replicas in the partition.</span></span>
            <span data-ttu-id="cf390-119">計算は、少数のレプリカの 1 つの障害を許容するように丸めます。</span><span class="sxs-lookup"><span data-stu-id="cf390-119">The computation rounds up to tolerate one failure on small numbers of replicas.</span></span> <span data-ttu-id="cf390-120">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="cf390-120">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="cf390-121">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="cf390-121">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyServices">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyServices" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyServices As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyServices : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cf390-122">取得または異常なサービスの最大許容パーセンテージを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf390-122">Gets or sets the maximum allowed percentage of unhealthy services.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cf390-123">許容される異常なサービスの割合の最大値を返します。</span><span class="sxs-lookup"><span data-stu-id="cf390-123">Returns the maximum allowed percentage of unhealthy services.</span></span> <span data-ttu-id="cf390-124">使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</span><span class="sxs-lookup"><span data-stu-id="cf390-124">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="cf390-125">パーセンテージは、サービスことのできる正常なアプリケーションがエラーと見なされるまでの最大許容パーセンテージを表します。</span><span class="sxs-lookup"><span data-stu-id="cf390-125">The percentage represents the maximum tolerated percentage of services that can be unhealthy before the application is considered in error.</span></span> <span data-ttu-id="cf390-126">割合が守られて異常な場合に、少なくとも 1 つのサービスがある場合は、正常性は警告として評価されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-126">If the percentage is respected but there is at least one unhealthy service, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="cf390-127">これは、特定のサービス型のサービスの合計数を特定のサービスの種類の問題のあるサービスの数で割ることによって計算されます。</span><span class="sxs-lookup"><span data-stu-id="cf390-127">This is calculated by dividing the number of unhealthy services of the specific service type over the total number of services of the specific service type.</span></span>
            <span data-ttu-id="cf390-128">計算は、少数のサービスの 1 つの障害を許容するように丸めます。</span><span class="sxs-lookup"><span data-stu-id="cf390-128">The computation rounds up to tolerate one failure on small numbers of services.</span></span> <span data-ttu-id="cf390-129">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="cf390-129">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="cf390-130">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="cf390-130">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceTypeHealthPolicy.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cf390-131">サービスの種類の正常性ポリシーの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="cf390-131">Gets a string representation of the service type health policy.</span></span>
            </summary>
        <returns><span data-ttu-id="cf390-132">サービスの種類の正常性ポリシーの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="cf390-132">A string representation of the service type health policy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>