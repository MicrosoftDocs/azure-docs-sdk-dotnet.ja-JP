<Type Name="Resource" FullName="Microsoft.Azure.Documents.Resource">
  <TypeSignature Language="C#" Value="public abstract class Resource : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Resource extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Resource&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type Resource = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> 
             Azure Cosmos DB サービスのリソースを抽象型を表します。
             すべての Azure Cosmos DB リソースなど<see cref="T:Microsoft.Azure.Documents.Database" />、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />、および<see cref="T:Microsoft.Azure.Documents.Document" />この抽象型を拡張します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Resource" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Resource (Microsoft.Azure.Documents.Resource resource);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Resource resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.#ctor(Microsoft.Azure.Documents.Resource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Resource : Microsoft.Azure.Documents.Resource -&gt; Microsoft.Azure.Documents.Resource" Usage="new Microsoft.Azure.Documents.Resource resource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Documents.Resource" />
      </Parameters>
      <Docs>
        <param name="resource">To be added.</param>
        <summary>
            コピー コンス トラクター、 <see cref="T:Microsoft.Azure.Documents.Resource" /> Cosmos DB の Azure サービスで使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AltLink">
      <MemberSignature Language="C#" Value="public string AltLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AltLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberSignature Language="VB.NET" Value="Public Property AltLink As String" />
      <MemberSignature Language="F#" Value="member this.AltLink : string with get, set" Usage="Microsoft.Azure.Documents.Resource.AltLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからリソースに関連付けられた、alt キーを押しリンクを取得します。
            </summary>
        <value>リソースに関連付けられた alt キーをリンクします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Documents.Resource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからリソースに関連付けられているエンティティ タグを取得します。
            </summary>
        <value>
            リソースに関連付けられているエンティティ タグ。
            </value>
        <remarks>
            Etag は、同時実行制御チェックのリソースを更新するときに使用されます。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyValue&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetPropertyValue&lt;T&gt; (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetPropertyValue&lt;T&gt;(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.GetPropertyValue``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyValue(Of T) (propertyName As String) As T" />
      <MemberSignature Language="F#" Value="member this.GetPropertyValue : string -&gt; 'T" Usage="resource.GetPropertyValue propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">プロパティの型。</typeparam>
        <param name="propertyName">プロパティの名前。</param>
        <summary>
            Azure Cosmos DB サービスから、指定したプロパティ名に関連付けられているプロパティの値を取得します。
            </summary>
        <returns>プロパティ値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public virtual string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Documents.Resource.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
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
            取得または Azure Cosmos DB サービスのリソースの Id を設定します。
            </summary>
        <value>リソースに関連付けられている Id です。</value>
        <remarks>
          <para>
            Azure Cosmos DB データベース アカウント内のすべてのリソースには、一意の識別子が必要です。 異なり<see cref="P:Microsoft.Azure.Documents.Resource.ResourceId" />、内部的に設定される、この Id はユーザーによって設定は不変ではありません。
            </para>
          <para>
            ドキュメント リソースを使用する場合は、この設定可能な Id プロパティがあるすぎます。 Id が、ユーザーが指定されていない場合、SDK は自動的に新しい GUID を生成し、データベース内のドキュメントを保存する前に、このプロパティにその値を代入します。 DisableAutomaticIdGeneration パラメーターを設定してこの自動 Id の生成をオーバーライドすることができます、<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />インスタンスは true に設定します。
            これにより、SDK で新しい Id を生成できなくなります。 
            </para>
          <para>
            次の文字は制限されており、Id プロパティでは使用できません: '/'、'\\','?'、'#'
             </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public virtual string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Documents.Resource.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_rid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのリソースに関連付けられているリソース Id を設定します。
            </summary>
        <value>
            リソースに関連付けられているリソース Id です。
            </value>
        <remarks>
            リソース Id は、データベース、コレクションまたはドキュメントであるかどうかは、各 Azure Cosmos DB リソースに割り当てられている、変更できない場合は、一意の識別子です。
            SelfLinks、データベース アカウント内の各リソースの静的アドレス指定可能な Uri を作成するときに、これらのリソース id が使用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Documents.Resource.SelfLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_self")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自己リンク Cosmos DB の Azure サービスからリソースに関連付けられたを取得します。
            </summary>
        <value>自己リンクされたリソースに関連付けられています。</value>
        <remarks>
            自己リンク データベース アカウント内の各リソースの静的アドレス指定可能な Uri は、Azure Cosmos DB リソース モデルに従います。
            例:  ドキュメントの自己リンクと db/db_resourceid/colls/coll_resourceid/ドキュメント/doc_resourceid 可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertyValue">
      <MemberSignature Language="C#" Value="public void SetPropertyValue (string propertyName, object propertyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetPropertyValue(string propertyName, object propertyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.SetPropertyValue(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetPropertyValue (propertyName As String, propertyValue As Object)" />
      <MemberSignature Language="F#" Value="member this.SetPropertyValue : string * obj -&gt; unit" Usage="resource.SetPropertyValue (propertyName, propertyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="propertyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="propertyName">プロパティの名前。</param>
        <param name="propertyValue">プロパティ値。</param>
        <summary>
            Azure Cosmos DB サービスの指定したプロパティ名に関連付けられているプロパティの値を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public virtual DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.Documents.Resource.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.UnixDateTimeConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_ts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからリソースに関連付けられた最終変更タイムスタンプを取得します。
            </summary>
        <value>リソースに関連付けられている最終変更タイムスタンプ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToByteArray">
      <MemberSignature Language="C#" Value="public byte[] ToByteArray ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ToByteArray() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Resource.ToByteArray" />
      <MemberSignature Language="VB.NET" Value="Public Function ToByteArray () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ToByteArray : unit -&gt; byte[]" Usage="resource.ToByteArray " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure Cosmos DB サービスの SaveTo を使用してバイト配列にシリアル化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>