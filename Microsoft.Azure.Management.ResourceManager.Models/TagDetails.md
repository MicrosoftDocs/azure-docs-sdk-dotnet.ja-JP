<Type Name="TagDetails" FullName="Microsoft.Azure.Management.ResourceManager.Models.TagDetails">
  <TypeSignature Language="C#" Value="public class TagDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TagDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.TagDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class TagDetails" />
  <TypeSignature Language="F#" Value="type TagDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タグの詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TagDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagDetails (string id = null, string tagName = null, Microsoft.Azure.Management.ResourceManager.Models.TagCount count = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tagName, class Microsoft.Azure.Management.ResourceManager.Models.TagCount count, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.TagCount,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.TagValue})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional tagName As String = null, Optional count As TagCount = null, Optional values As IList(Of TagValue) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.TagDetails : string * string * Microsoft.Azure.Management.ResourceManager.Models.TagCount * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.TagDetails" Usage="new Microsoft.Azure.Management.ResourceManager.Models.TagDetails (id, tagName, count, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="count" Type="Microsoft.Azure.Management.ResourceManager.Models.TagCount" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;" />
      </Parameters>
      <Docs>
        <param name="id">タグ id。</param>
        <param name="tagName">タグ名。</param>
        <param name="count">リソース タグを使用するリソースの合計数。 タグは、最初が作成され、関連付けられているリソースを持たず、ときに、値は 0 です。</param>
        <param name="values">タグ値のリスト。</param>
        <summary>
            TagDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.TagCount Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.TagCount Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As TagCount" />
      <MemberSignature Language="F#" Value="member this.Count : Microsoft.Azure.Management.ResourceManager.Models.TagCount with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TagCount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース タグを使用するリソースの合計数を設定します。 タグは、最初が作成され、関連付けられているリソースを持たず、ときに、値は 0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または設定、タグ id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagName">
      <MemberSignature Language="C#" Value="public string TagName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.TagName" />
      <MemberSignature Language="VB.NET" Value="Public Property TagName As String" />
      <MemberSignature Language="F#" Value="member this.TagName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.TagDetails.TagName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tagName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタグ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of TagValue)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.TagDetails.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタグ値の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>