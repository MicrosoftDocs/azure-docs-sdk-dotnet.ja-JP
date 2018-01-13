<Type Name="IPRule" FullName="Microsoft.Azure.Management.Storage.Models.IPRule">
  <TypeSignature Language="C#" Value="public class IPRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.IPRule" />
  <TypeSignature Language="VB.NET" Value="Public Class IPRule" />
  <TypeSignature Language="F#" Value="type IPRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="21ca0-101">特定の IP または IP と IP ルールは、CIDR 形式で範囲です。</span><span class="sxs-lookup"><span data-stu-id="21ca0-101">IP rule with specific IP or IP range in CIDR format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.IPRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21ca0-102">IPRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="21ca0-102">Initializes a new instance of the IPRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPRule (string iPAddressOrRange, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; action = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string iPAddressOrRange, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Action&gt; action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.IPRule.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.Action})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (iPAddressOrRange As String, Optional action As Nullable(Of Action) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.IPRule : string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; -&gt; Microsoft.Azure.Management.Storage.Models.IPRule" Usage="new Microsoft.Azure.Management.Storage.Models.IPRule (iPAddressOrRange, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="iPAddressOrRange" Type="System.String" />
        <Parameter Name="action" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt;" />
      </Parameters>
      <Docs>
        <param name="iPAddressOrRange"><span data-ttu-id="21ca0-103">指定の IP アドレスまたは IP CIDR 形式で範囲です。</span><span class="sxs-lookup"><span data-stu-id="21ca0-103">Specifies the IP or IP range in CIDR format.</span></span> <span data-ttu-id="21ca0-104">IPV4 アドレスだけが許可されます。</span><span class="sxs-lookup"><span data-stu-id="21ca0-104">Only IPV4 address is allowed.</span></span></param>
        <param name="action"><span data-ttu-id="21ca0-105">IP の ACL ルールのアクション。</span><span class="sxs-lookup"><span data-stu-id="21ca0-105">The action of IP ACL rule.</span></span> <span data-ttu-id="21ca0-106">使用可能な値が含まれます: 'Allow'</span><span class="sxs-lookup"><span data-stu-id="21ca0-106">Possible values include: 'Allow'</span></span></param>
        <summary>
            <span data-ttu-id="21ca0-107">IPRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="21ca0-107">Initializes a new instance of the IPRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Action&gt; Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.IPRule.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As Nullable(Of Action)" />
      <MemberSignature Language="F#" Value="member this.Action : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.IPRule.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Action&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21ca0-108">取得または IP ACL ルールのアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="21ca0-108">Gets or sets the action of IP ACL rule.</span></span> <span data-ttu-id="21ca0-109">使用可能な値が含まれます: 'Allow'</span><span class="sxs-lookup"><span data-stu-id="21ca0-109">Possible values include: 'Allow'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrRange">
      <MemberSignature Language="C#" Value="public string IPAddressOrRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddressOrRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.IPRule.IPAddressOrRange" />
      <MemberSignature Language="VB.NET" Value="Public Property IPAddressOrRange As String" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrRange : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.IPRule.IPAddressOrRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21ca0-110">取得または設定を示す、IP アドレスまたは IP CIDR 形式で範囲です。</span><span class="sxs-lookup"><span data-stu-id="21ca0-110">Gets or sets specifies the IP or IP range in CIDR format.</span></span> <span data-ttu-id="21ca0-111">IPV4 アドレスだけが許可されます。</span><span class="sxs-lookup"><span data-stu-id="21ca0-111">Only IPV4 address is allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.IPRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="iPRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21ca0-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="21ca0-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="21ca0-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21ca0-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>