<Type Name="ApplicationGatewaySslPolicy" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationGatewaySslPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewaySslPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewaySslPolicy" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaySslPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="de19c-101">アプリケーション ゲートウェイ SSL ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="de19c-101">Application gateway SSL policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de19c-102">ApplicationGatewaySslPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de19c-102">Initializes a new instance of the ApplicationGatewaySslPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPolicy (System.Collections.Generic.IList&lt;string&gt; disabledSslProtocols = null, string policyType = null, string policyName = null, System.Collections.Generic.IList&lt;string&gt; cipherSuites = null, string minProtocolVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; disabledSslProtocols, string policyType, string policyName, class System.Collections.Generic.IList`1&lt;string&gt; cipherSuites, string minProtocolVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional disabledSslProtocols As IList(Of String) = null, Optional policyType As String = null, Optional policyName As String = null, Optional cipherSuites As IList(Of String) = null, Optional minProtocolVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy : System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy (disabledSslProtocols, policyType, policyName, cipherSuites, minProtocolVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disabledSslProtocols" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cipherSuites" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="minProtocolVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="disabledSslProtocols">To be added.</param>
        <param name="policyType">To be added.</param>
        <param name="policyName">To be added.</param>
        <param name="cipherSuites">To be added.</param>
        <param name="minProtocolVersion">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CipherSuites">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CipherSuites { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CipherSuites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.CipherSuites" />
      <MemberSignature Language="VB.NET" Value="Public Property CipherSuites As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CipherSuites : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.CipherSuites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cipherSuites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledSslProtocols">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DisabledSslProtocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DisabledSslProtocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.DisabledSslProtocols" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledSslProtocols As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DisabledSslProtocols : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.DisabledSslProtocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledSslProtocols")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de19c-103">取得または設定 SSL プロトコルを使用してアプリケーション ゲートウェイでは無効にします。</span><span class="sxs-lookup"><span data-stu-id="de19c-103">Gets or sets SSL protocols to be disabled on application gateway.</span></span>
            <span data-ttu-id="de19c-104">使用可能な値が: 'TLSv1_0'、'TLSv1_1' および 'TLSv1_2' です。</span><span class="sxs-lookup"><span data-stu-id="de19c-104">Possible values are: 'TLSv1_0', 'TLSv1_1', and 'TLSv1_2'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinProtocolVersion">
      <MemberSignature Language="C#" Value="public string MinProtocolVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinProtocolVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.MinProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property MinProtocolVersion As String" />
      <MemberSignature Language="F#" Value="member this.MinProtocolVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.MinProtocolVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minProtocolVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPolicy.PolicyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>