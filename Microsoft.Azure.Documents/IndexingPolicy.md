<Type Name="IndexingPolicy" FullName="Microsoft.Azure.Documents.IndexingPolicy">
  <TypeSignature Language="C#" Value="public sealed class IndexingPolicy : Microsoft.Azure.Documents.JsonSerializable, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IndexingPolicy extends Microsoft.Azure.Documents.JsonSerializable implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IndexingPolicy&#xA;Inherits JsonSerializable&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type IndexingPolicy = class&#xA;    inherit JsonSerializable&#xA;    interface ICloneable" />
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
            Azure Cosmos DB サービスのコレクションのインデックス作成ポリシーの構成を表します。
            </summary>
    <remarks>
            インデックス作成ポリシー プロパティ (JSON パス) が含まれている/除外されるインデックスがオプトイン ドキュメントごと、および有効桁数とパスごとにインデックスの種類と一貫して更新またはオフラインの (遅延)、自動であるかどうかを構成するために使用できます。
            <para>参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/</see>インデックス作成ポリシーを指定する方法についての追加。</para></remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.#ctor" />
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>
            インデックス作成モードは consistent に設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingPolicy (params Microsoft.Azure.Documents.Index[] defaultIndexOverrides);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Index[] defaultIndexOverrides) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.#ctor(Microsoft.Azure.Documents.Index[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray defaultIndexOverrides As Index())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.IndexingPolicy : Microsoft.Azure.Documents.Index[] -&gt; Microsoft.Azure.Documents.IndexingPolicy" Usage="new Microsoft.Azure.Documents.IndexingPolicy defaultIndexOverrides" />
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
        <Parameter Name="defaultIndexOverrides" Type="Microsoft.Azure.Documents.Index[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="defaultIndexOverrides">ルート パスの既定のインデックス仕様として機能するインデックスのコンマ区切りのセット。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.IndexingPolicy" /> Azure Cosmos DB サービスのルート パスの既定のインデックス仕様としてインデックスの指定したセットを持つクラス。
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Index" />
        <example>
            次の例では、ルートのパスに対して既定 indexingPolicy をオーバーライドする方法を示します。
            <code language="c#"><![CDATA[
            HashIndex hashIndexOverride = Index.Hash(DataType.String, 5);
            RangeIndex rangeIndexOverride = Index.Range(DataType.Number, 2);
            SpatialIndex spatialIndexOverride = Index.Spatial(DataType.Point);
            
            IndexingPolicy indexingPolicy = new IndexingPolicy(hashIndexOverride, rangeIndexOverride, spatialIndexOverride);
            ]]></code></example>
        <example>
            だけの番号、indexingPolicy を上書きしたい場合は、だけを指定できます。
            <code language="c#"><![CDATA[
            RangeIndex rangeIndexOverride = Index.Range(DataType.Number, 2);
            
            IndexingPolicy indexingPolicy = new IndexingPolicy(rangeIndexOverride);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Automatic">
      <MemberSignature Language="C#" Value="public bool Automatic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Automatic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.Automatic" />
      <MemberSignature Language="VB.NET" Value="Public Property Automatic As Boolean" />
      <MemberSignature Language="F#" Value="member this.Automatic : bool with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.Automatic" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="automatic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのコレクションの自動インデックス作成が有効になっているかどうかを示す値を設定します。
            </summary>
        <value>
            自動インデックス作成が有効である場合は true。それ以外の場合は false です。
            </value>
        <remarks>
            自動インデックス作成では、ドキュメントに明示的にから除外することを使用して<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />です。  
            手動インデックスのドキュメントを明示的に追加することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IndexingPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="indexingPolicy.Clone " />
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
            Azure Cosmos DB サービスのインデックス作成ポリシーの詳細コピーを実行します。
            </summary>
        <returns>
            インデックス作成ポリシーの複製。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludedPaths">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt; ExcludedPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.ExcludedPath&gt; ExcludedPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.ExcludedPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludedPaths As Collection(Of ExcludedPath)" />
      <MemberSignature Language="F#" Value="member this.ExcludedPaths : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt; with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.ExcludedPaths" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="excludedPaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.ExcludedPath&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を含むコレクション<see cref="T:Microsoft.Azure.Documents.ExcludedPath" />Cosmos DB の Azure サービス内のオブジェクト。
            </summary>
        <value>
            コレクションを含む<see cref="T:Microsoft.Azure.Documents.ExcludedPath" />オブジェクト。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedPaths">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt; IncludedPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.IncludedPath&gt; IncludedPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.IncludedPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludedPaths As Collection(Of IncludedPath)" />
      <MemberSignature Language="F#" Value="member this.IncludedPaths : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt; with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.IncludedPaths" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedPaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.IncludedPath&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を含むコレクション<see cref="T:Microsoft.Azure.Documents.IncludedPath" />Cosmos DB の Azure サービス内のオブジェクト。
            </summary>
        <value>
            コレクションを含む<see cref="T:Microsoft.Azure.Documents.IncludedPath" />オブジェクト。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingMode IndexingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.IndexingMode IndexingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IndexingPolicy.IndexingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingMode As IndexingMode" />
      <MemberSignature Language="F#" Value="member this.IndexingMode : Microsoft.Azure.Documents.IndexingMode with get, set" Usage="Microsoft.Azure.Documents.IndexingPolicy.IndexingMode" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexingMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスでインデックス作成モード (一貫性のあるまたは遅延) を設定します。
            </summary>
        <value>
            値のいずれか、<see cref="T:Microsoft.Azure.Documents.IndexingMode" />列挙します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>