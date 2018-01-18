<Type Name="ClusterHealthPolicy" FullName="System.Fabric.Health.ClusterHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterHealthPolicy = class" />
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
      <para><span data-ttu-id="9a023-101">クラスターまたはクラスター ノードの正常性を評価する正常性ポリシーを定義します。</span><span class="sxs-lookup"><span data-stu-id="9a023-101">Defines a health policy used to evaluate the health of the cluster or of a cluster node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="9a023-102"><see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9a023-102">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="9a023-103">既定では、エラーまたは警告が許容されません。</span><span class="sxs-lookup"><span data-stu-id="9a023-103">By default, no errors or warnings are tolerated.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationTypeHealthPolicyMap ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeHealthPolicyMap As ApplicationTypeHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeHealthPolicyMap : System.Fabric.Health.ApplicationTypeHealthPolicyMap" Usage="System.Fabric.Health.ClusterHealthPolicy.ApplicationTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationTypeHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="9a023-104">アプリケーションの種類名ごとに MaxPercentUnhealthyApplications でマップを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a023-104">Gets the map with MaxPercentUnhealthyApplications per application type name.</span></span> 
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="9a023-105">アプリケーション型正常性ポリシー マップ MaxPercentUnhealthyApplications とアプリケーションの種類名ごとです。</span><span class="sxs-lookup"><span data-stu-id="9a023-105">The application type health policy map with MaxPercentUnhealthyApplications per application type name.</span></span></para>
        </value>
        <remarks>
          <span data-ttu-id="9a023-106"><para>アプリケーションの種類の正常性ポリシー マップは、特殊なアプリケーションの種類を記述するクラスターの正常性評価で使用できます。既定では、すべてのアプリケーションのプールに配置し、を使用して評価<see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />です。1 つまたは複数のアプリケーションの種類の特殊なし、する必要がありますを別の方法で扱われる、グローバル プールから取得およびできますマップで、アプリケーションの型名に関連付けられている割合に対して評価されます。たとえば、クラスターには、異なる種類の数千ものアプリケーションがあり、特別なアプリケーションの種類の制御アプリケーション インスタンスの数はわずかです。制御アプリケーションがエラー状態になることはありません。そのユーザーは、いくつかの障害を許容するように 20% が"ControlApplicationType"、MaxPercentUnhealthyApplications を 0 に設定するアプリケーションの種類に対してグローバル MaxPercentUnhealthyApplications を指定できます。このようにすると、多くのアプリケーションのうちのいくつかが異常でも、グローバルな異常のパーセンテージを下回っている場合、クラスターは警告と評価されます。警告の正常性状態はクラスターのアップグレードや、エラーの正常性状態によりトリガーされる他の監視には影響しません。エラーの 1 つでも管理アプリケーションはクラスターの正常性エラーがロールバックまたは、クラスターのアップグレードを妨げるです。</para>&gt;<para>マップで定義されているアプリケーションの種類、すべてのアプリケーション インスタンスが作成され、アプリケーションのグローバル プール外です。これらは、マップの特定の MaxPercentUnhealthyApplications を使用して、該当するアプリケーションの種類のアプリケーションの総数に基づいて評価されます。アプリケーションのすべての残りの部分は、グローバル プール内に残りますされ、MaxPercentUnhealthyApplications で評価されます。</para><para>クラスター マニフェストでは、特定のアプリケーションの種類のエントリを定義するに FabricSettings 内のエントリを追加のパラメーター プレフィックス「ApplicationTypeMaxPercentUnhealthyApplications-」続けてによって形成される名前を持つアプリケーションの種類の名前です。</para> <para>MaxPercentUnhealthyApplications 既定値を評価に使用するアプリケーションの種類のポリシーが指定されていない場合</para>。<para>EnableApplicationTypeHealthEvaluation で、クラスターが構成されている場合にのみ、アプリケーションの種類の正常性評価が行われます<languageKeyword>true</languageKeyword>です。既定では、設定を無効にします。</para></span><span class="sxs-lookup"><span data-stu-id="9a023-106"><para>The application type health policy map can be used during cluster health evaluation to describe special application types. By default, all applications are put into a pool and evaluated with <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />. If one or more application types are special and should be treated in a different way, they can be taken out of the global pool and evaluated against the percentages associated with their application type name in the map. For example, in a cluster there are thousands of applications of different types, and a few control application instances of a special application type. The control applications should never be in error. So users can specify global MaxPercentUnhealthyApplications to 20% to tolerate some failures, but for the application type "ControlApplicationType" set the MaxPercentUnhealthyApplications to 0. This way, if some of the many applications are unhealthy, but below the global unhealthy percentage, the cluster would be evaluated to Warning. A warning health state does not impact cluster upgrade or other monitoring triggered by Error health state. But even one control application in error would make cluster health error, which can rollback or prevent a cluster upgrade. </para>&gt; <para>For the application types defined in the map, all application instances are taken out of the global pool of applications. They are evaluated based on the total number of applications of the application type, using the specific MaxPercentUnhealthyApplications from the map. All the rest of the applications remain in the global pool and are evaluated with MaxPercentUnhealthyApplications.</para><para>To define entries for the specific application types in the cluster manifest, inside FabricSettings add entries for parameters with name formed by prefix "ApplicationTypeMaxPercentUnhealthyApplications-" followed by application type name.</para><para>If no policy is specified for an application type, the default MaxPercentUnhealthyApplications is used for evaluation.</para><para>The application type health evaluation is done only when the cluster is configured with EnableApplicationTypeHealthEvaluation <languageKeyword>true</languageKeyword>. The setting is disabled by default. </para></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.ConsiderWarningAsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="9a023-107">取得または設定、<see cref="T:System.Boolean" />エラーとして重大度が同じで、警告状態を持つレポートを扱う必要があるかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="9a023-107">Gets or sets a <see cref="T:System.Boolean" /> that determines whether reports with warning state should be treated with the same severity as errors.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="9a023-108"><languageKeyword>true</languageKeyword>場合は警告状態を持つレポートをエラーとして扱う必要があります<languageKeyword>false</languageKeyword>場合は警告をエラーとして扱うことはできません。</span><span class="sxs-lookup"><span data-stu-id="9a023-108"><languageKeyword>true</languageKeyword> if reports with warning state should be treated as errors; <languageKeyword>false</languageKeyword> if warnings should not be treated as errors.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />
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
          <para><span data-ttu-id="9a023-109">取得または異常なアプリケーションの許可される最大の割合を設定します。</span><span class="sxs-lookup"><span data-stu-id="9a023-109">Gets or sets the maximum allowed percentage of unhealthy applications.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9a023-110">許容される異常なアプリケーションの割合の最大値。</span><span class="sxs-lookup"><span data-stu-id="9a023-110">The maximum allowed percentage of unhealthy applications.</span></span> <span data-ttu-id="9a023-111">有効な値は、0 から 100 までの整数値です。</span><span class="sxs-lookup"><span data-stu-id="9a023-111">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="9a023-112">パーセンテージは、異常な可能性のあるアプリケーションの最大許容パーセンテージを表します。この値を超えるとクラスターはエラーの状態と見なされます。</span><span class="sxs-lookup"><span data-stu-id="9a023-112">The percentage represents the maximum tolerated percentage of applications that can be unhealthy before the cluster is considered in error.</span></span> <span data-ttu-id="9a023-113">許容パーセンテージ内であっても、1 つ以上の異常なアプリケーションがある場合は、正常性は Warning として評価されます。</span><span class="sxs-lookup"><span data-stu-id="9a023-113">If the percentage is respected but there is at least one unhealthy application, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="9a023-114">これには、計算に含まれているアプリケーションの種類のすべてのアプリケーションの除外、クラスターに配置されたアプリケーションの総数に対して異常なアプリケーションの数で割ることによって、<see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />です。</span><span class="sxs-lookup"><span data-stu-id="9a023-114">This is calculated by dividing the number of unhealthy applications over the total number of applications deployed in the cluster, excluding all applications of application types that are included in the <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span></span>
            <span data-ttu-id="9a023-115">切り上げ計算が実行され、少数のアプリケーションに対する 1 つのエラーは許容されます。</span><span class="sxs-lookup"><span data-stu-id="9a023-115">The computation rounds up to tolerate one failure on small numbers of applications.</span></span> <span data-ttu-id="9a023-116">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="9a023-116">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="9a023-117">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="9a023-117">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyNodes" />
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
          <para><span data-ttu-id="9a023-118">取得または異常なノードの最大許容パーセンテージを設定します。</span><span class="sxs-lookup"><span data-stu-id="9a023-118">Gets or sets the maximum allowed percentage of unhealthy nodes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9a023-119">許容される異常なノードの割合の最大値。</span><span class="sxs-lookup"><span data-stu-id="9a023-119">The maximum allowed percentage of unhealthy nodes.</span></span> <span data-ttu-id="9a023-120">有効な値は、0 から 100 までの整数値です。</span><span class="sxs-lookup"><span data-stu-id="9a023-120">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="9a023-121">パーセンテージは、異常な可能性のあるノードの最大許容パーセンテージを表します。この値を超えるとクラスターはエラーの状態と見なされます。</span><span class="sxs-lookup"><span data-stu-id="9a023-121">The percentage represents the maximum tolerated percentage of nodes that can be unhealthy before the cluster is considered in error.</span></span> <span data-ttu-id="9a023-122">許容パーセンテージ内であっても、1 つ以上の異常なノードがある場合は、正常性は Warning として評価されます。</span><span class="sxs-lookup"><span data-stu-id="9a023-122">If the percentage is respected but there is at least one unhealthy node, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="9a023-123">これは、クラスター内のノードの総数に対して異常なノードの数で割ることによって計算されます。</span><span class="sxs-lookup"><span data-stu-id="9a023-123">This is calculated by dividing the number of unhealthy nodes over the total number of nodes in the cluster.</span></span>
            <span data-ttu-id="9a023-124">切り上げ計算が実行され、少数のノードに対する 1 つのエラーは許容されます。</span><span class="sxs-lookup"><span data-stu-id="9a023-124">The computation rounds up to tolerate one failure on small numbers of nodes.</span></span> <span data-ttu-id="9a023-125">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="9a023-125">Default percentage: zero.</span></span>
            </para>
          <para><span data-ttu-id="9a023-126">大規模なクラスターでは、ダウンしているか修復を必要とするノードがいくつか必ず存在するため、それが許容されるようにこのパーセンテージを構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9a023-126">In large clusters, some nodes will always be down or out for repairs, so this percentage should be configured to tolerate that.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="9a023-127">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="9a023-127">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthPolicy.ToString " />
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
            <span data-ttu-id="9a023-128">クラスターの正常性ポリシーの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="9a023-128">Gets a string representation of the cluster health policy.</span></span>
            </summary>
        <returns><span data-ttu-id="9a023-129">クラスターの正常性ポリシーの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="9a023-129">A string representation of the cluster health policy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>