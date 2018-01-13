<Type Name="CloudServiceConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration">
  <TypeSignature Language="C#" Value="public class CloudServiceConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudServiceConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudServiceConfiguration" />
  <TypeSignature Language="F#" Value="type CloudServiceConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe092-101">Azure クラウド サービス プラットフォームに基づいて、プール内のノードで構成します。</span><span class="sxs-lookup"><span data-stu-id="fe092-101">The configuration for nodes in a pool based on the Azure Cloud Services platform.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe092-102">CloudServiceConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe092-102">Initializes a new instance of the CloudServiceConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration (string osFamily, string targetOSVersion = null, string currentOSVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string osFamily, string targetOSVersion, string currentOSVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osFamily As String, Optional targetOSVersion As String = null, Optional currentOSVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration (osFamily, targetOSVersion, currentOSVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osFamily" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="currentOSVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osFamily"><span data-ttu-id="fe092-103">プール内の仮想マシンにインストールする Azure ゲスト OS ファミリ。</span><span class="sxs-lookup"><span data-stu-id="fe092-103">The Azure Guest OS family to be installed on the virtual machines in the pool.</span></span></param>
        <param name="targetOSVersion"><span data-ttu-id="fe092-104">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</span><span class="sxs-lookup"><span data-stu-id="fe092-104">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="currentOSVersion"><span data-ttu-id="fe092-105">現在、プール内の仮想マシンにインストールされている Azure ゲスト OS のバージョン。</span><span class="sxs-lookup"><span data-stu-id="fe092-105">The Azure Guest OS Version currently installed on the virtual machines in the pool.</span></span></param>
        <summary>
            <span data-ttu-id="fe092-106">CloudServiceConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe092-106">Initializes a new instance of the CloudServiceConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentOSVersion">
      <MemberSignature Language="C#" Value="public string CurrentOSVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.CurrentOSVersion : string" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe092-107">現在、プール内の仮想マシンにインストールされている Azure ゲスト OS バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="fe092-107">Gets the Azure Guest OS Version currently installed on the virtual machines in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fe092-108">TargetOSVersion 異なるプールの状態がアップグレードする場合はこれがあります。</span><span class="sxs-lookup"><span data-stu-id="fe092-108">This may differ from targetOSVersion if the pool state is Upgrading.</span></span> <span data-ttu-id="fe092-109">ここでは一部の仮想マシンが、targetOSVersion にあります。、アップグレード プロセス中に、currentOSVersion でいくつかあります。</span><span class="sxs-lookup"><span data-stu-id="fe092-109">In this case some virtual machines may be on the targetOSVersion and some may be on the currentOSVersion during the upgrade process.</span></span> <span data-ttu-id="fe092-110">すべての仮想マシンのアップグレードが currentOSVersion は targetOSVersion と同じであるに更新されます。</span><span class="sxs-lookup"><span data-stu-id="fe092-110">Once all virtual machines have upgraded, currentOSVersion is updated to be the same as targetOSVersion.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsFamily">
      <MemberSignature Language="C#" Value="public string OsFamily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsFamily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.OsFamily" />
      <MemberSignature Language="VB.NET" Value="Public Property OsFamily As String" />
      <MemberSignature Language="F#" Value="member this.OsFamily : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.OsFamily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osFamily")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe092-111">取得またはプール内の仮想マシンにインストールされている Azure ゲスト OS ファミリを設定します。</span><span class="sxs-lookup"><span data-stu-id="fe092-111">Gets or sets the Azure Guest OS family to be installed on the virtual machines in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fe092-112">指定できる値は: 2 - OS ファミリ 2、Windows Server 2008 R2 SP1 に相当します。</span><span class="sxs-lookup"><span data-stu-id="fe092-112">Possible values are: 2 - OS Family 2, equivalent to Windows Server 2008 R2 SP1.</span></span> <span data-ttu-id="fe092-113">3-OS ファミリ 3、Windows Server 2012 に相当します。</span><span class="sxs-lookup"><span data-stu-id="fe092-113">3 - OS Family 3, equivalent to Windows Server 2012.</span></span> <span data-ttu-id="fe092-114">4</span><span class="sxs-lookup"><span data-stu-id="fe092-114">4</span></span>
            - <span data-ttu-id="fe092-115">OS ファミリ 4、Windows Server 2012 R2 に相当します。</span><span class="sxs-lookup"><span data-stu-id="fe092-115">OS Family 4, equivalent to Windows Server 2012 R2.</span></span> <span data-ttu-id="fe092-116">5-OS ファミリの 5、Windows Server 2016 に相当します。</span><span class="sxs-lookup"><span data-stu-id="fe092-116">5 - OS Family 5, equivalent to Windows Server 2016.</span></span> <span data-ttu-id="fe092-117">詳細については、Azure ゲスト OS リリース (https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/#releases) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fe092-117">For more information, see Azure Guest OS Releases (https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/#releases).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetOSVersion">
      <MemberSignature Language="C#" Value="public string TargetOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetOSVersion : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe092-118">取得またはプール内の仮想マシンにインストールされている Azure ゲスト OS バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="fe092-118">Gets or sets the Azure Guest OS version to be installed on the virtual machines in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fe092-119">既定値は \* 指定された OS ファミリの最新のオペレーティング システムのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="fe092-119">The default value is \* which specifies the latest operating system version for the specified OS family.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudServiceConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe092-120">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fe092-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fe092-121">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fe092-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>