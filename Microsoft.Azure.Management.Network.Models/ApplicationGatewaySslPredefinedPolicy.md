<Type Name="ApplicationGatewaySslPredefinedPolicy" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationGatewaySslPredefinedPolicy : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewaySslPredefinedPolicy extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewaySslPredefinedPolicy&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaySslPredefinedPolicy = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="42e75-101">定義済みの Ssl ポリシー</span><span class="sxs-lookup"><span data-stu-id="42e75-101">An Ssl predefined policy</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPredefinedPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42e75-102">ApplicationGatewaySslPredefinedPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42e75-102">Initializes a new instance of the ApplicationGatewaySslPredefinedPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPredefinedPolicy (string id = null, string name = null, System.Collections.Generic.IList&lt;string&gt; cipherSuites = null, string minProtocolVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, class System.Collections.Generic.IList`1&lt;string&gt; cipherSuites, string minProtocolVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional cipherSuites As IList(Of String) = null, Optional minProtocolVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy : string * string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy (id, name, cipherSuites, minProtocolVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cipherSuites" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="minProtocolVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="42e75-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="42e75-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="42e75-104">Ssl の名前には、ポリシーが定義されています。</span><span class="sxs-lookup"><span data-stu-id="42e75-104">Name of Ssl predefined policy.</span></span></param>
        <param name="cipherSuites"><span data-ttu-id="42e75-105">アプリケーション ゲートウェイの指定した順序で有効にする Ssl 暗号スイート。</span><span class="sxs-lookup"><span data-stu-id="42e75-105">Ssl cipher suites to be enabled in the specified order for application gateway.</span></span></param>
        <param name="minProtocolVersion"><span data-ttu-id="42e75-106">アプリケーション ゲートウェイでサポートされるために Ssl プロトコルの最小バージョン。</span><span class="sxs-lookup"><span data-stu-id="42e75-106">Minimum version of Ssl protocol to be supported on application gateway.</span></span> <span data-ttu-id="42e75-107">使用可能な値が含まれます: 'TLSv1_0'、'TLSv1_1'、'TLSv1_2'</span><span class="sxs-lookup"><span data-stu-id="42e75-107">Possible values include: 'TLSv1_0', 'TLSv1_1', 'TLSv1_2'</span></span></param>
        <summary>
            <span data-ttu-id="42e75-108">ApplicationGatewaySslPredefinedPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42e75-108">Initializes a new instance of the ApplicationGatewaySslPredefinedPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CipherSuites">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CipherSuites { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CipherSuites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.CipherSuites" />
      <MemberSignature Language="VB.NET" Value="Public Property CipherSuites As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CipherSuites : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.CipherSuites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cipherSuites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42e75-109">取得またはアプリケーション ゲートウェイの指定した順序で有効にする ssl 暗号スイートを設定します。</span><span class="sxs-lookup"><span data-stu-id="42e75-109">Gets or sets ssl cipher suites to be enabled in the specified order for application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinProtocolVersion">
      <MemberSignature Language="C#" Value="public string MinProtocolVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinProtocolVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.MinProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property MinProtocolVersion As String" />
      <MemberSignature Language="F#" Value="member this.MinProtocolVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.MinProtocolVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minProtocolVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42e75-110">取得またはアプリケーション ゲートウェイでサポートされるために Ssl プロトコルの最小バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="42e75-110">Gets or sets minimum version of Ssl protocol to be supported on application gateway.</span></span> <span data-ttu-id="42e75-111">使用可能な値が含まれます: 'TLSv1_0'、'TLSv1_1'、'TLSv1_2'</span><span class="sxs-lookup"><span data-stu-id="42e75-111">Possible values include: 'TLSv1_0', 'TLSv1_1', 'TLSv1_2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPredefinedPolicy.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42e75-112">取得または定義済みの Ssl ポリシーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="42e75-112">Gets or sets name of Ssl predefined policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>