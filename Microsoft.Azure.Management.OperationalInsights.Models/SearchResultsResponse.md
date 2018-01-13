<Type Name="SearchResultsResponse" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse">
  <TypeSignature Language="C#" Value="public class SearchResultsResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchResultsResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchResultsResponse" />
  <TypeSignature Language="F#" Value="type SearchResultsResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            検索結果を get 操作応答です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchResultsResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SearchResultsResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchResultsResponse (string id = null, Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata metadata = null, System.Collections.Generic.IList&lt;object&gt; value = null, Microsoft.Azure.Management.OperationalInsights.Models.SearchError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata metadata, class System.Collections.Generic.IList`1&lt;object&gt; value, class Microsoft.Azure.Management.OperationalInsights.Models.SearchError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.#ctor(System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata,System.Collections.Generic.IList{System.Object},Microsoft.Azure.Management.OperationalInsights.Models.SearchError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional metadata As SearchMetadata = null, Optional value As IList(Of Object) = null, Optional error As SearchError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse : string * Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata * System.Collections.Generic.IList&lt;obj&gt; * Microsoft.Azure.Management.OperationalInsights.Models.SearchError -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse (id, metadata, value, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="metadata" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchError" />
      </Parameters>
      <Docs>
        <param name="id">完全な url が含まれている検索の id です。</param>
        <param name="metadata">検索結果からのメタデータ。</param>
        <param name="value">結果の値の配列。</param>
        <param name="error">エラーです。</param>
        <summary>
            SearchResultsResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.SearchError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.SearchError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As SearchError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.OperationalInsights.Models.SearchError with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定エラー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            完全な url が含まれている検索の id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As SearchMetadata" />
      <MemberSignature Language="F#" Value="member this.Metadata : Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="__metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または検索結果からメタデータを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または結果の値の配列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>