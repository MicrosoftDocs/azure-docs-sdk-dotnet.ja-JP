<Type Name="ApplicationHealthPolicy" FullName="System.Fabric.Health.ApplicationHealthPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationHealthPolicy" />
  <TypeSignature Language="F#" Value="type ApplicationHealthPolicy = class" />
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
      <para><span data-ttu-id="cee5a-101">Service Fabric アプリケーションまたはその子エンティティを 1 つの正常性を評価する正常性ポリシーを定義します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-101">Defines a health policy used to evaluate the health of a Service Fabric application or one of its children entities.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="cee5a-102"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-102">Initializes a new instance of the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="cee5a-103">既定のアプリケーションの正常性ポリシーには、エラーまたは警告を許容しません。</span><span class="sxs-lookup"><span data-stu-id="cee5a-103">The default application health policy doesn't tolerate any errors or warnings.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
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
          <para><span data-ttu-id="cee5a-104">取得または設定、<see cref="T:System.Boolean" />エラーとして重大度が同じで、警告状態を持つレポートを扱う必要があるかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-104">Gets or sets a <see cref="T:System.Boolean" /> that determines whether reports with warning state should be treated with the same severity as errors.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="cee5a-105"><languageKeyword>true</languageKeyword>場合は警告状態を持つレポートをエラーとして扱う必要があります<languageKeyword>false</languageKeyword>とき警告エラーとして処理するされません。</span><span class="sxs-lookup"><span data-stu-id="cee5a-105"><languageKeyword>true</languageKeyword> if reports with warning state should be treated as errors; <languageKeyword>false</languageKeyword> when warnings should not be treated as errors.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultServiceTypeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultServiceTypeHealthPolicy As ServiceTypeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.DefaultServiceTypeHealthPolicy : System.Fabric.Health.ServiceTypeHealthPolicy with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceTypeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cee5a-106">取得または、既定では、サービスの種類のヘルスを評価するために使用する正常性ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-106">Gets or sets the health policy used by default to evaluate the health of a service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cee5a-107"><see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />サービスの種類のポリシーが定義されていない場合は、サービスの種類の正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-107">The <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> used to evaluate service type health if no service type policy is defined.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
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
          <para><span data-ttu-id="cee5a-108">取得または異常な展開済みアプリケーションの許可される最大の割合を設定します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-108">Gets or sets the maximum allowed percentage of unhealthy deployed applications.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cee5a-109">許容される異常な展開済みアプリケーションの割合の最大値。</span><span class="sxs-lookup"><span data-stu-id="cee5a-109">The maximum allowed percentage of unhealthy deployed applications.</span></span> <span data-ttu-id="cee5a-110">使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</span><span class="sxs-lookup"><span data-stu-id="cee5a-110">Allowed values are <see cref="T:System.Byte" /> values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="cee5a-111">パーセンテージは、ことのできる正常なアプリケーションがエラーと見なされる前に配置されているアプリケーションの最大許容パーセンテージを表します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-111">The percentage represents the maximum tolerated percentage of deployed applications that can be unhealthy before the application is considered in error.</span></span> <span data-ttu-id="cee5a-112">これは、アプリケーションがクラスター内に展開される現在のノード数にわたって異常な展開済みアプリケーションの数で割ることによって計算されます。</span><span class="sxs-lookup"><span data-stu-id="cee5a-112">This is calculated by dividing the number of unhealthy deployed applications over the number of nodes that the applications are currently deployed on in the cluster.</span></span>
            <span data-ttu-id="cee5a-113">切り上げ計算が実行され、少数のノードに対する 1 つのエラーは許容されます。</span><span class="sxs-lookup"><span data-stu-id="cee5a-113">The computation rounds up to tolerate one failure on small numbers of nodes.</span></span> <span data-ttu-id="cee5a-114">既定のパーセンテージは 0 です。</span><span class="sxs-lookup"><span data-stu-id="cee5a-114">Default percentage: zero.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="cee5a-115">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="cee5a-115">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeHealthPolicyMap As IDictionary(Of String, ServiceTypeHealthPolicy)" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeHealthPolicyMap : System.Collections.Generic.IDictionary&lt;string, System.Fabric.Health.ServiceTypeHealthPolicy&gt;" Usage="System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Fabric.Health.ServiceTypeHealthPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cee5a-116">取得または設定を持つマップ<see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />あたりサービス型の名前。</span><span class="sxs-lookup"><span data-stu-id="cee5a-116">Gets or sets the map with <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> per service type name.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="cee5a-117">サービスの種類の正常性ポリシー サービスの種類名ごとにマップします。</span><span class="sxs-lookup"><span data-stu-id="cee5a-117">The map with service type health policy per service type name.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="cee5a-118">マップ内のエントリは、指定されたサービスの種類ごとに既定のサービス型の正常性ポリシーを置き換えます。</span><span class="sxs-lookup"><span data-stu-id="cee5a-118">The entries in the map replace the default service type health policy for each specified service type.</span></span>
            <span data-ttu-id="cee5a-119">たとえば、アプリケーションでは、ステートレスなゲートウェイ サービスの種類とステートフル エンジン サービスの種類の両方を含む、ステートレスおよびステートフルなサービスの正常性ポリシー構成できる方法が異なります。</span><span class="sxs-lookup"><span data-stu-id="cee5a-119">For example, in an application that contains both a stateless gateway service type and a stateful engine service type, the health policies for the stateless and stateful services can be configured differently.</span></span>
            <span data-ttu-id="cee5a-120">サービスの種類ごとのポリシーには、サービスのヘルスをより細かく制御します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-120">With policy per service type, there's more granular control of the health of the service.</span></span>
            </para>
          <para><span data-ttu-id="cee5a-121">サービス型の名前のポリシーが指定されていない場合、<see cref="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />評価に使用します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-121">If no policy is specified for a service type name, the <see cref="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" /> is used for evaluation.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthPolicy.ToString " />
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
            <span data-ttu-id="cee5a-122">アプリケーションの正常性ポリシーの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="cee5a-122">Gets a string representation of the application health policy.</span></span>
            </summary>
        <returns><span data-ttu-id="cee5a-123">アプリケーションの正常性ポリシーの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="cee5a-123">A string representation of the application health policy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>