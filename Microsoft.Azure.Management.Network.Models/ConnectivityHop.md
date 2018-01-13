<Type Name="ConnectivityHop" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityHop">
  <TypeSignature Language="C#" Value="public class ConnectivityHop" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityHop extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityHop" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityHop" />
  <TypeSignature Language="F#" Value="type ConnectivityHop = class" />
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
            ソースと宛先の間のホップについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityHop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityHop.#ctor" />
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
            ConnectivityHop クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityHop (string type = null, string id = null, string address = null, string resourceId = null, System.Collections.Generic.IList&lt;string&gt; nextHopIds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; issues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string id, string address, string resourceId, class System.Collections.Generic.IList`1&lt;string&gt; nextHopIds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; issues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityHop.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ConnectivityIssue})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional id As String = null, Optional address As String = null, Optional resourceId As String = null, Optional nextHopIds As IList(Of String) = null, Optional issues As IList(Of ConnectivityIssue) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityHop : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityHop" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityHop (type, id, address, resourceId, nextHopIds, issues)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="nextHopIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="issues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;" />
      </Parameters>
      <Docs>
        <param name="type">ホップの種類。</param>
        <param name="id">ホップの ID です。</param>
        <param name="address">ホップの IP アドレス。</param>
        <param name="resourceId">このホップに対応するリソースの ID。</param>
        <param name="nextHopIds">次のホップ識別子の一覧。</param>
        <param name="issues">問題の一覧です。</param>
        <summary>
            ConnectivityHop クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ホップの IP アドレスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ホップの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; Issues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; Issues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Issues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issues As IList(Of ConnectivityIssue)" />
      <MemberSignature Language="F#" Value="member this.Issues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Issues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            問題の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NextHopIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NextHopIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.NextHopIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHopIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NextHopIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.NextHopIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            次のホップ識別子の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このホップに対応するリソースの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ホップの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>