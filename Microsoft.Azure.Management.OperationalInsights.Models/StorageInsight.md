<Type Name="StorageInsight" FullName="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight">
  <TypeSignature Language="C#" Value="public class StorageInsight : Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageInsight extends Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageInsight&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type StorageInsight = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            最上位レベルのストレージ インサイト リソースのコンテナーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsight ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageInsight クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsight (Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount storageAccount, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;string&gt; containers = null, System.Collections.Generic.IList&lt;string&gt; tables = null, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus status = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount storageAccount, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;string&gt; containers, class System.Collections.Generic.IList`1&lt;string&gt; tables, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus status, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.#ctor(Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight : Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight (storageAccount, id, name, type, tags, containers, tables, status, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="containers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="tables" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount">ストレージ アカウント接続の詳細</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">リソース タグ</param>
        <param name="containers">ワークスペースを読み取る必要がありますの blob コンテナーの名前</param>
        <param name="tables">お読みくださいワークスペースを Azure のテーブルの名前</param>
        <param name="status">記憶域 insight の状態</param>
        <param name="eTag">記憶域 insight の ETag。</param>
        <summary>
            StorageInsight クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Containers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Containers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Containers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Containers" />
      <MemberSignature Language="VB.NET" Value="Public Property Containers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Containers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Containers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースを読み取る必要がありますの blob コンテナーの名前を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または記憶域 insight の ETag を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As StorageInsightStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            記憶域 insight の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccount" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストレージ アカウント接続の詳細の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Tables" />
      <MemberSignature Language="VB.NET" Value="Public Property Tables As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tables : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Tables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定お読みくださいワークスペースを Azure のテーブルの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageInsight.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>