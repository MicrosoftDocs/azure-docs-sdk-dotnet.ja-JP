<Type Name="SpatialIndex" FullName="Microsoft.Azure.Documents.SpatialIndex">
  <TypeSignature Language="C#" Value="public sealed class SpatialIndex : Microsoft.Azure.Documents.Index, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SpatialIndex extends Microsoft.Azure.Documents.Index implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SpatialIndex" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SpatialIndex&#xA;Inherits Index&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type SpatialIndex = class&#xA;    inherit Index&#xA;    interface ICloneable" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Index</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            インスタンスを指定します、 <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
    <remarks>
            空間クエリを処理するために使用します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SpatialIndex (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SpatialIndex.#ctor(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SpatialIndex : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.SpatialIndex" Usage="new Microsoft.Azure.Documents.SpatialIndex dataType" />
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
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType">インデックスのパス指定の対象のデータ型を指定します</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.SpatialIndex.DataType" />
        <example>
            データ型を渡して SpatialIndex クラスのインスタンスを作成する例を次に示します
            <code language="c#"><![CDATA[
            SpatialIndex spatialIndex = new SpatialIndex(DataType.Point);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SpatialIndex.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="spatialIndex.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ICloneable.Clone</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure Cosmos DB サービスの空間インデックスのコピーを作成します。
            </summary>
        <returns>空間インデックスの複製。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.DataType DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.DataType DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SpatialIndex.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As DataType" />
      <MemberSignature Language="F#" Value="member this.DataType : Microsoft.Azure.Documents.DataType with get, set" Usage="Microsoft.Azure.Documents.SpatialIndex.DataType" />
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
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのこのインデックスを適用する対象のデータ型を設定します。
            </summary>
        <value>
            データ型は、このインデックスが適用する必要があります。
            </value>
        <remarks>有効な値の範囲 http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy を参照してください。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>