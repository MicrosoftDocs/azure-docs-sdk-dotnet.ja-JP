<Type Name="BgpPeerStatusListResult" FullName="Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult">
  <TypeSignature Language="C#" Value="public class BgpPeerStatusListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpPeerStatusListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpPeerStatusListResult" />
  <TypeSignature Language="F#" Value="type BgpPeerStatusListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="15652-101">BGP ピアの状態 API サービスの一覧について応答を呼び出す</span><span class="sxs-lookup"><span data-stu-id="15652-101">Response for list BGP peer status API service call</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatusListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult.#ctor" />
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
            <span data-ttu-id="15652-102">BgpPeerStatusListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="15652-102">Initializes a new instance of the BgpPeerStatusListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatusListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BgpPeerStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of BgpPeerStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" Usage="new Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="15652-103">BGP ピアの一覧</span><span class="sxs-lookup"><span data-stu-id="15652-103">List of BGP peers</span></span></param>
        <summary>
            <span data-ttu-id="15652-104">BgpPeerStatusListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="15652-104">Initializes a new instance of the BgpPeerStatusListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of BgpPeerStatus)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15652-105">取得または設定の BGP ピアの一覧</span><span class="sxs-lookup"><span data-stu-id="15652-105">Gets or sets list of BGP peers</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>