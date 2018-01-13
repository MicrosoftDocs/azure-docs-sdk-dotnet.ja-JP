<Type Name="IncludedPath" FullName="Microsoft.Azure.Documents.IncludedPath">
  <TypeSignature Language="C#" Value="public sealed class IncludedPath : Microsoft.Azure.Documents.JsonSerializable, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IncludedPath extends Microsoft.Azure.Documents.JsonSerializable implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IncludedPath" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IncludedPath&#xA;Inherits JsonSerializable&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type IncludedPath = class&#xA;    inherit JsonSerializable&#xA;    interface ICloneable" />
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
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary> 
            Cosmos DB の Azure サービスに含まれる JSON ドキュメント内のパスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IncludedPath ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IncludedPath.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IncludedPath.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="includedPath.Clone " />
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
            Azure Cosmos DB サービスのインクルード パスのコピーを作成します。 
            </summary>
        <returns>インクルード パスの複製。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt; Indexes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.Index&gt; Indexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IncludedPath.Indexes" />
      <MemberSignature Language="VB.NET" Value="Public Property Indexes As Collection(Of Index)" />
      <MemberSignature Language="F#" Value="member this.Indexes : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt; with get, set" Usage="Microsoft.Azure.Documents.IncludedPath.Indexes" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のコレクション<see cref="T:Microsoft.Azure.Documents.Index" />Cosmos DB の Azure サービスでこのインクルード パスに適用するオブジェクト。
            </summary>
        <value>
            コレクション、<see cref="T:Microsoft.Azure.Documents.Index" />このインクルード パスに適用するオブジェクト。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IncludedPath.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Documents.IncludedPath.Path" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスでインデックスを作成するパスを設定します。
            </summary>
        <value>
            インデックスを作成するパス。
            </value>
        <remarks>
            パスを指定する方法について http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy を参照してください。
            有効な例をいくつか:"prop"//?、"prop"//* *、/"prop"/"subprop"/?、"prop"///しますか?
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>