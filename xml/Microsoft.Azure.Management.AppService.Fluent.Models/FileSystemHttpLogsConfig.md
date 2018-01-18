<Type Name="FileSystemHttpLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig">
  <TypeSignature Language="C#" Value="public class FileSystemHttpLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemHttpLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemHttpLogsConfig" />
  <TypeSignature Language="F#" Value="type FileSystemHttpLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="daaff-101">Http ログ ファイルのシステム構成にします。</span><span class="sxs-lookup"><span data-stu-id="daaff-101">Http logs to file system configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemHttpLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="daaff-102">FileSystemHttpLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="daaff-102">Initializes a new instance of the FileSystemHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemHttpLogsConfig (Nullable&lt;int&gt; retentionInMb = null, Nullable&lt;int&gt; retentionInDays = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; retentionInMb, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retentionInMb As Nullable(Of Integer) = null, Optional retentionInDays As Nullable(Of Integer) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig (retentionInMb, retentionInDays, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retentionInMb" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="retentionInMb"><span data-ttu-id="daaff-103">Http ログ ファイルが使用できるメガバイト単位で最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="daaff-103">Maximum size in megabytes that http log files can use.</span></span>
            <span data-ttu-id="daaff-104">古いに達したときに、新規の領域をログ ファイルが削除されません。</span><span class="sxs-lookup"><span data-stu-id="daaff-104">When reached old log files will be removed to make space for new ones.</span></span>
            <span data-ttu-id="daaff-105">25 ~ 100 の範囲値の範囲はします。</span><span class="sxs-lookup"><span data-stu-id="daaff-105">Value can range between 25 and 100.</span></span></param>
        <param name="retentionInDays"><span data-ttu-id="daaff-106">保有期間日数。</span><span class="sxs-lookup"><span data-stu-id="daaff-106">Retention in days.</span></span>
            <span data-ttu-id="daaff-107">次の日数より古いファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="daaff-107">Remove files older than X days.</span></span>
            <span data-ttu-id="daaff-108">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="daaff-108">0 or lower means no retention.</span></span></param>
        <param name="enabled"><span data-ttu-id="daaff-109">有効になります。</span><span class="sxs-lookup"><span data-stu-id="daaff-109">Enabled.</span></span></param>
        <summary>
            <span data-ttu-id="daaff-110">FileSystemHttpLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="daaff-110">Initializes a new instance of the FileSystemHttpLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daaff-111">取得または設定が有効にします。</span><span class="sxs-lookup"><span data-stu-id="daaff-111">Gets or sets enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daaff-112">取得または保有期間を日に設定します。</span><span class="sxs-lookup"><span data-stu-id="daaff-112">Gets or sets retention in days.</span></span>
            <span data-ttu-id="daaff-113">次の日数より古いファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="daaff-113">Remove files older than X days.</span></span>
            <span data-ttu-id="daaff-114">0 または下には、保有期間、なしです。</span><span class="sxs-lookup"><span data-stu-id="daaff-114">0 or lower means no retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInMb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInMb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInMb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInMb" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInMb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInMb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInMb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInMb")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daaff-115">取得または http ログ ファイルが使用できるメガバイト単位で最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="daaff-115">Gets or sets maximum size in megabytes that http log files can use.</span></span>
            <span data-ttu-id="daaff-116">古いに達したときに、新規の領域をログ ファイルが削除されません。</span><span class="sxs-lookup"><span data-stu-id="daaff-116">When reached old log files will be removed to make space for new ones.</span></span>
            <span data-ttu-id="daaff-117">25 ~ 100 の範囲値の範囲はします。</span><span class="sxs-lookup"><span data-stu-id="daaff-117">Value can range between 25 and 100.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileSystemHttpLogsConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="daaff-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="daaff-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="daaff-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="daaff-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>