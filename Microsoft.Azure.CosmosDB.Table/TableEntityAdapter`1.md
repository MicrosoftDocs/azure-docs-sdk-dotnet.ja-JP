<Type Name="TableEntityAdapter&lt;T&gt;" FullName="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class TableEntityAdapter&lt;T&gt; : Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableEntityAdapter`1&lt;T&gt; extends Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntityAdapter(Of T)&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type TableEntityAdapter&lt;'T&gt; = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.CosmosDB.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">読み書きを Azure テーブル ストレージでは、クラスまたは構造体を使用できますのオブジェクトの型。</typeparam>
    <summary>
            読み取りとから継承せず、オブジェクトを Azure テーブル ストレージに書き込みを許可するアダプター クラス<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />クラスの実装または<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />インターフェイスです。 オブジェクトには、単純な POCO オブジェクトまたは入れ子になった複雑なプロパティを含む複合オブジェクトを指定できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; originalEntity" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
      </Parameters>
      <Docs>
        <param name="originalEntity">Azure テーブル ストレージに書き込むオブジェクト。</param>
        <summary>
            指定されたオブジェクトで <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity, string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity, string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T, partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T * string * string -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; (originalEntity, partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalEntity">Azure テーブル ストレージに書き込むオブジェクト。</param>
        <param name="partitionKey">エンティティのパーティション キー値を表す文字列。</param>
        <param name="rowKey">エンティティの行のキー値を含む文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />指定したオブジェクト、パーティション キーと行キーを持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalEntity">
      <MemberSignature Language="C#" Value="public T OriginalEntity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T OriginalEntity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalEntity As T" />
      <MemberSignature Language="F#" Value="member this.OriginalEntity : 'T with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;.OriginalEntity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            読み取りし、書き込みは azure テーブル ストレージにある元のエンティティです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public override void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="tableEntityAdapter.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:System.Collections.Generic.IDictionary`2" />プロパティをマップするオブジェクト名を入力して<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />値。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            逆シリアル化<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />インスタンスの指定を使用して<see cref="T:System.Collections.Generic.IDictionary`2" />のプロパティ名をマップする、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />に型指定された<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />、値に格納、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="tableEntityAdapter.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値から、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</returns>
        <remarks>場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />単純なプロパティ (プリミティブ型、string, byte[],...) を持つ単純な POCO オブジェクト<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドは、作成<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />オブジェクトをこれらのプロパティを使用します。<br />
             Ie です。 使用して、単純な POCO オブジェクト A B および C のプロパティを持つこの構造体 A -&gt;B、A-&gt;{"B", EntityProperty(B)} のキー値のペアに変換される C, {"C", EntityProperty(C)}。<br />
            場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />複雑なプロパティ (および可能性のある独自の複雑なプロパティを持つこれらのプロパティ) を持つ<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドが平坦化<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />最初。<br />
            Ie です。 B の単純なプロパティと、この構造では A - E と F の独自のプロパティである必要が C および D の複雑なプロパティを持つオブジェクト A&gt;B、A -&gt;C -&gt;E と A -&gt;d-&gt;F はキーの値をフラット化します。ペア。<br />
            {"B", EntityProperty(B)}、{"C_E", EntityProperty(E)} と {"D_F"、EntityProperty(F)}。<br />
            キーの値のペアごとに。<br />
            1. 「_」で区切られた最後のノード プロパティ (E または F) に、ルート (A) からアクセスしたプロパティの名前を追加することによって構成されます。<br />
            2. 値が、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />オブジェクト、最後のノード プロパティの値によってインスタンス化します。<br />
            すべてのキー値のペアが格納される、返された<see cref="T:System.Collections.Generic.IDictionary`2" />です。<br /><see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />メソッドは、元 (POCO または複合型) を使用してオブジェクトを recomposes、<see cref="T:System.Collections.Generic.IDictionary`2" />格納して、このメソッドによって返される<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。<br />
            マークされたプロパティ<see cref="T:Microsoft.Azure.CosmosDB.Table.IgnorePropertyAttribute" />で、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />オブジェクトは無視され、このメソッドでは処理されません。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>