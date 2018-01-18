<Type Name="EffectiveNetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityGroup" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityGroup = class" />
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
            <span data-ttu-id="7e989-101">有効なネットワーク セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="7e989-101">Effective network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e989-102">EffectiveNetworkSecurityGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e989-102">Initializes a new instance of the EffectiveNetworkSecurityGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroup (Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup = null, Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation association = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; tagMap = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup, class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation association, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; tagMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkSecurityGroup As SubResource = null, Optional association As EffectiveNetworkSecurityGroupAssociation = null, Optional effectiveSecurityRules As IList(Of EffectiveNetworkSecurityRule) = null, Optional tagMap As IDictionary(Of String, IList(Of String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup (networkSecurityGroup, association, effectiveSecurityRules, tagMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="association" Type="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation" />
        <Parameter Name="effectiveSecurityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt;" />
        <Parameter Name="tagMap" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="networkSecurityGroup">To be added.</param>
        <param name="association">To be added.</param>
        <param name="effectiveSecurityRules">To be added.</param>
        <param name="tagMap">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Association">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation Association { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation Association" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.Association" />
      <MemberSignature Language="VB.NET" Value="Public Property Association As EffectiveNetworkSecurityGroupAssociation" />
      <MemberSignature Language="F#" Value="member this.Association : Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.Association" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="association")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EffectiveSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.EffectiveSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property EffectiveSecurityRules As IList(Of EffectiveNetworkSecurityRule)" />
      <MemberSignature Language="F#" Value="member this.EffectiveSecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.EffectiveSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="effectiveSecurityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e989-103">取得または効果的なセキュリティの規則のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="7e989-103">Gets or sets a collection of effective security rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e989-104">取得または適用されているネットワーク セキュリティ グループの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="7e989-104">Gets or sets the ID of network security group that is applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; TagMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; TagMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.TagMap" />
      <MemberSignature Language="VB.NET" Value="Public Property TagMap As IDictionary(Of String, IList(Of String))" />
      <MemberSignature Language="F#" Value="member this.TagMap : System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroup.TagMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tagMap")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>