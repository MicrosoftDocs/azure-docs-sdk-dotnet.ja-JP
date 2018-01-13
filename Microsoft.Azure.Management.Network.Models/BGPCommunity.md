<Type Name="BGPCommunity" FullName="Microsoft.Azure.Management.Network.Models.BGPCommunity">
  <TypeSignature Language="C#" Value="public class BGPCommunity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BGPCommunity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BGPCommunity" />
  <TypeSignature Language="VB.NET" Value="Public Class BGPCommunity" />
  <TypeSignature Language="F#" Value="type BGPCommunity = class" />
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
            サービスのコミュニティ リソースで提供される bgp コミュニティの情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BGPCommunity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BGPCommunity.#ctor" />
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
            BGPCommunity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BGPCommunity (string serviceSupportedRegion = null, string communityName = null, string communityValue = null, System.Collections.Generic.IList&lt;string&gt; communityPrefixes = null, Nullable&lt;bool&gt; isAuthorizedToUse = null, string serviceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceSupportedRegion, string communityName, string communityValue, class System.Collections.Generic.IList`1&lt;string&gt; communityPrefixes, valuetype System.Nullable`1&lt;bool&gt; isAuthorizedToUse, string serviceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BGPCommunity.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceSupportedRegion As String = null, Optional communityName As String = null, Optional communityValue As String = null, Optional communityPrefixes As IList(Of String) = null, Optional isAuthorizedToUse As Nullable(Of Boolean) = null, Optional serviceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BGPCommunity : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.BGPCommunity" Usage="new Microsoft.Azure.Management.Network.Models.BGPCommunity (serviceSupportedRegion, communityName, communityValue, communityPrefixes, isAuthorizedToUse, serviceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceSupportedRegion" Type="System.String" />
        <Parameter Name="communityName" Type="System.String" />
        <Parameter Name="communityValue" Type="System.String" />
        <Parameter Name="communityPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isAuthorizedToUse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="serviceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceSupportedRegion">サービスをサポートしている領域。 などの O365、領域は、グローバルです。</param>
        <param name="communityName">Bgp コミュニティの名前。 例: Skype。</param>
        <param name="communityValue">Bgp コミュニティの値。 詳細については: https://docs.microsoft.com/en-us/azure/expressroute/expressroute-routing です。</param>
        <param name="communityPrefixes">このプレフィックスは、bgp コミュニティが含まれています。</param>
        <param name="isAuthorizedToUse">顧客は、か、bgp コミュニティを使用する権限がします。</param>
        <param name="serviceGroup">Bgp コミュニティのサービス グループが含まれています。</param>
        <summary>
            BGPCommunity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityName">
      <MemberSignature Language="C#" Value="public string CommunityName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommunityName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityName" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityName As String" />
      <MemberSignature Language="F#" Value="member this.CommunityName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または bgp コミュニティの名前を設定します。 例: Skype。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CommunityPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CommunityPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CommunityPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または bgp community を含むプレフィックスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityValue">
      <MemberSignature Language="C#" Value="public string CommunityValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommunityValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityValue As String" />
      <MemberSignature Language="F#" Value="member this.CommunityValue : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.CommunityValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または bgp コミュニティの値を設定します。 詳細については: https://docs.microsoft.com/en-us/azure/expressroute/expressroute-routing です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAuthorizedToUse">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAuthorizedToUse { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAuthorizedToUse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.IsAuthorizedToUse" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAuthorizedToUse As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAuthorizedToUse : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.IsAuthorizedToUse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAuthorizedToUse")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定か、bgp コミュニティを使用する顧客が承認されています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceGroup">
      <MemberSignature Language="C#" Value="public string ServiceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.ServiceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ServiceGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.ServiceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、bgp コミュニティのサービス グループが含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceSupportedRegion">
      <MemberSignature Language="C#" Value="public string ServiceSupportedRegion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceSupportedRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BGPCommunity.ServiceSupportedRegion" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceSupportedRegion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceSupportedRegion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BGPCommunity.ServiceSupportedRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceSupportedRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービスをサポートする地域を設定します。 などの O365、領域は、グローバルです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>