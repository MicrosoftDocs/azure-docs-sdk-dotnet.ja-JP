<Type Name="VaultUsage" FullName="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage">
  <TypeSignature Language="C#" Value="public class VaultUsage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultUsage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultUsage" />
  <TypeSignature Language="F#" Value="type VaultUsage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71f48-101">資格情報コンテナーの使用法。</span><span class="sxs-lookup"><span data-stu-id="71f48-101">Usages of a vault.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71f48-102">VaultUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71f48-102">Initializes a new instance of the VaultUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultUsage (string unit = null, string quotaPeriod = null, Nullable&lt;DateTime&gt; nextResetTime = null, Nullable&lt;long&gt; currentValue = null, Nullable&lt;long&gt; limit = null, Microsoft.Azure.Management.RecoveryServices.Models.NameInfo name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string unit, string quotaPeriod, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime, valuetype System.Nullable`1&lt;int64&gt; currentValue, valuetype System.Nullable`1&lt;int64&gt; limit, class Microsoft.Azure.Management.RecoveryServices.Models.NameInfo name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.RecoveryServices.Models.NameInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional unit As String = null, Optional quotaPeriod As String = null, Optional nextResetTime As Nullable(Of DateTime) = null, Optional currentValue As Nullable(Of Long) = null, Optional limit As Nullable(Of Long) = null, Optional name As NameInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage : string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.RecoveryServices.Models.NameInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage (unit, quotaPeriod, nextResetTime, currentValue, limit, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="quotaPeriod" Type="System.String" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.RecoveryServices.Models.NameInfo" />
      </Parameters>
      <Docs>
        <param name="unit"><span data-ttu-id="71f48-103">使用状況の単位です。</span><span class="sxs-lookup"><span data-stu-id="71f48-103">Unit of the usage.</span></span> <span data-ttu-id="71f48-104">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'%'、'CountPerSecond'、'BytesPerSecond'</span><span class="sxs-lookup"><span data-stu-id="71f48-104">Possible values include: 'Count', 'Bytes', 'Seconds', 'Percent', 'CountPerSecond', 'BytesPerSecond'</span></span></param>
        <param name="quotaPeriod"><span data-ttu-id="71f48-105">使用状況クォータ期間。</span><span class="sxs-lookup"><span data-stu-id="71f48-105">Quota period of usage.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="71f48-106">次に使用状況の時刻をリセットします。</span><span class="sxs-lookup"><span data-stu-id="71f48-106">Next reset time of usage.</span></span></param>
        <param name="currentValue"><span data-ttu-id="71f48-107">使用状況の現在の値。</span><span class="sxs-lookup"><span data-stu-id="71f48-107">Current value of usage.</span></span></param>
        <param name="limit"><span data-ttu-id="71f48-108">使用状況の制限。</span><span class="sxs-lookup"><span data-stu-id="71f48-108">Limit of usage.</span></span></param>
        <param name="name"><span data-ttu-id="71f48-109">使用法の名前です。</span><span class="sxs-lookup"><span data-stu-id="71f48-109">Name of usage.</span></span></param>
        <summary>
            <span data-ttu-id="71f48-110">VaultUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71f48-110">Initializes a new instance of the VaultUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-111">取得または使用状況の現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-111">Gets or sets current value of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-112">取得または使用率の制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-112">Gets or sets limit of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.NameInfo Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.NameInfo Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As NameInfo" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.RecoveryServices.Models.NameInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.NameInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-113">取得または使用法の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-113">Gets or sets name of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-114">取得または使用状況の次回のリセットを設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-114">Gets or sets next reset time of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotaPeriod">
      <MemberSignature Language="C#" Value="public string QuotaPeriod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotaPeriod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.QuotaPeriod" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotaPeriod As String" />
      <MemberSignature Language="F#" Value="member this.QuotaPeriod : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.QuotaPeriod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotaPeriod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-115">取得または使用量のクォータの期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-115">Gets or sets quota period of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71f48-116">取得または使用率の単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="71f48-116">Gets or sets unit of the usage.</span></span> <span data-ttu-id="71f48-117">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'%'、'CountPerSecond'、'BytesPerSecond'</span><span class="sxs-lookup"><span data-stu-id="71f48-117">Possible values include: 'Count', 'Bytes', 'Seconds', 'Percent', 'CountPerSecond', 'BytesPerSecond'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>