<Type Name="RedisFirewallRule" FullName="Microsoft.Azure.Management.Redis.Models.RedisFirewallRule">
  <TypeSignature Language="C#" Value="public class RedisFirewallRule : Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisFirewallRule extends Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisFirewallRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RedisFirewallRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="07401-101">Redis キャッシュ上のファイアウォール規則は、名前があり、連続した接続を許可する IP アドレス範囲を説明します</span><span class="sxs-lookup"><span data-stu-id="07401-101">A firewall rule on a redis cache has a name, and describes a contiguous range of IP addresses permitted to connect</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisFirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07401-102">RedisFirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07401-102">Initializes a new instance of the RedisFirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisFirewallRule (string startIP, string endIP, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIP, string endIP, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIP As String, endIP As String, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisFirewallRule : string * string * string * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisFirewallRule" Usage="new Microsoft.Azure.Management.Redis.Models.RedisFirewallRule (startIP, endIP, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIP" Type="System.String" />
        <Parameter Name="endIP" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIP"><span data-ttu-id="07401-103">範囲に含まれる最下位の IP アドレス</span><span class="sxs-lookup"><span data-stu-id="07401-103">lowest IP address included in the range</span></span></param>
        <param name="endIP"><span data-ttu-id="07401-104">範囲に含まれる最上位の IP アドレス</span><span class="sxs-lookup"><span data-stu-id="07401-104">highest IP address included in the range</span></span></param>
        <param name="id"><span data-ttu-id="07401-105">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="07401-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="07401-106">リソース名。</span><span class="sxs-lookup"><span data-stu-id="07401-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="07401-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="07401-107">Resource type.</span></span></param>
        <summary>
            <span data-ttu-id="07401-108">RedisFirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07401-108">Initializes a new instance of the RedisFirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIP">
      <MemberSignature Language="C#" Value="public string EndIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.EndIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIP As String" />
      <MemberSignature Language="F#" Value="member this.EndIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.EndIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07401-109">取得または設定の範囲に含まれる最上位の IP アドレス</span><span class="sxs-lookup"><span data-stu-id="07401-109">Gets or sets highest IP address included in the range</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIP">
      <MemberSignature Language="C#" Value="public string StartIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.StartIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIP As String" />
      <MemberSignature Language="F#" Value="member this.StartIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.StartIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07401-110">取得または設定の範囲に含まれる最下位の IP アドレス</span><span class="sxs-lookup"><span data-stu-id="07401-110">Gets or sets lowest IP address included in the range</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisFirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisFirewallRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07401-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="07401-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07401-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="07401-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>