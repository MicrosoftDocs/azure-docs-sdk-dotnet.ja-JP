<Type Name="TableBatchOperation" FullName="Microsoft.Azure.CosmosDB.Table.TableBatchOperation">
  <TypeSignature Language="C#" Value="public sealed class TableBatchOperation : System.Collections.Generic.ICollection&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;, System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableBatchOperation extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.CosmosDB.Table.TableOperation&gt;, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.TableOperation&gt;, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableOperation&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableBatchOperation&#xA;Implements ICollection(Of TableOperation), IEnumerable(Of TableOperation), IList(Of TableOperation)" />
  <TypeSignature Language="F#" Value="type TableBatchOperation = class&#xA;    interface IList&lt;TableOperation&gt;&#xA;    interface ICollection&lt;TableOperation&gt;&#xA;    interface seq&lt;TableOperation&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            テーブルに対するバッチ操作を表します。
            </summary>
    <remarks>
      <para>呼び出すことによって、記憶域サービスの REST API によって単一のアトミック操作として実行されるテーブル操作のコレクションは、バッチ操作は、<a href="http://msdn.microsoft.com/en-us/library/windowsazure/dd894038.aspx">エンティティ グループ トランザクション</a>です。</para>
      <para>バッチ操作には、各操作のエンティティが同じパーティション キーを持つ必要があります、要件と、最大 100 の個々 のテーブル操作を含めることがあります。 取得操作のバッチには、他の操作を含めることはできません。 バッチ操作の合計ペイロードは 4 MB に制限されるに注意してください。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableBatchOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.#ctor" />
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
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.Azure.CosmosDB.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class Microsoft.Azure.CosmosDB.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Add(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member Add : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; unit&#xA;override this.Add : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; unit" Usage="tableBatchOperation.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />に追加する項目、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。</param>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> を <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> に追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="tableBatchOperation.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべてを消去<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />オブジェクトから、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.CosmosDB.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class Microsoft.Azure.CosmosDB.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Contains(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As TableOperation) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; bool&#xA;override this.Contains : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; bool" Usage="tableBatchOperation.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を検索する項目。</param>
        <summary>
            返します<c>true</c>この<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />指定した要素が含まれています。
            </summary>
        <returns>
          <c>true</c>にアイテムが含まれている場合、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。<c>false</c>、それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (Microsoft.Azure.CosmosDB.Table.TableOperation[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class Microsoft.Azure.CosmosDB.Table.TableOperation[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.CopyTo(Microsoft.Azure.CosmosDB.Table.TableOperation[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As TableOperation(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : Microsoft.Azure.CosmosDB.Table.TableOperation[] * int -&gt; unit&#xA;override this.CopyTo : Microsoft.Azure.CosmosDB.Table.TableOperation[] * int -&gt; unit" Usage="tableBatchOperation.CopyTo (array, arrayIndex)" />
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
        <Parameter Name="array" Type="Microsoft.Azure.CosmosDB.Table.TableOperation[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">コピーされた要素のシリアル化先として機能する 1 次元配列、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。</param>
        <param name="arrayIndex">開始するコピー先配列のインデックス。</param>
        <summary>
            すべての要素をコピー、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />指定したコピー先配列インデックスを開始位置指定の 1 次元配列にします。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作の数を取得<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。
            </summary>
        <value>操作の数、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Delete(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Delete : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Delete entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">テーブルから削除するエンティティ。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルから、指定されたエンティティを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.CosmosDB.Table.TableOperation&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;" Usage="tableBatchOperation.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.TableOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Collections.Generic.IEnumerator`1" /> の <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> を返します。
            </summary>
        <returns><see cref="T:System.Collections.IEnumerator" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />項目。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (Microsoft.Azure.CosmosDB.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class Microsoft.Azure.CosmosDB.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.IndexOf(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As TableOperation) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; int&#xA;override this.IndexOf : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; int" Usage="tableBatchOperation.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を検索する項目。</param>
        <summary>
            最初に見つかった位置の指定した 0 から始まるインデックスを返します<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />項目、または-1 の場合、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />アイテムが含まれていません。
            </summary>
        <returns>内の項目の最初に見つかった位置の 0 から始まるインデックス、 <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />、それ以外の場合は、– 1。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Insert entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">テーブルに挿入するエンティティ。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに指定されたエンティティを挿入します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (entity As ITableEntity, echoContent As Boolean)" />
      <MemberSignature Language="F#" Value="member this.Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity * bool -&gt; unit" Usage="tableBatchOperation.Insert (entity, echoContent)" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
        <Parameter Name="echoContent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="entity">テーブルに挿入するエンティティ。</param>
        <param name="echoContent">
          <c>true</c>場合は、挿入操作への応答で返される、それ以外のメッセージ ペイロードをする必要があります<c>false</c>です。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />バッチ操作の一環として、テーブルに指定されたエンティティを挿入するオブジェクト。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, Microsoft.Azure.CosmosDB.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class Microsoft.Azure.CosmosDB.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Insert(System.Int32,Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As TableOperation)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; unit&#xA;override this.Insert : int * Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; unit" Usage="tableBatchOperation.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="index">挿入する位置のインデックス、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />です。</param>
        <param name="item"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />挿入する項目。</param>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> を <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> 内の指定されたインデックス位置に挿入します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrMerge">
      <MemberSignature Language="C#" Value="public void InsertOrMerge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InsertOrMerge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.InsertOrMerge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub InsertOrMerge (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.InsertOrMerge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.InsertOrMerge entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">内容がされているエンティティを挿入またはマージします。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />エンティティが存在しない場合、テーブルに指定されたエンティティを挿入する以外の場合は、エンティティが存在し、その内容と共にマージされます、指定されたエンティティ。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrReplace">
      <MemberSignature Language="C#" Value="public void InsertOrReplace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void InsertOrReplace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.InsertOrReplace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub InsertOrReplace (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.InsertOrReplace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.InsertOrReplace entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">内容がされているエンティティを挿入または置換します。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />エンティティが存在しない場合、テーブルに指定されたエンティティを挿入する以外の場合は、エンティティが存在する場合は、指定したエンティティにその内容が置き換えられます。 します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.Azure.CosmosDB.Table.TableBatchOperation.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> が読み取り専用であるかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />は読み取り専用です。<c>false</c>、それ以外の場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableOperation this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableOperation Item(int32)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As TableOperation" />
      <MemberSignature Language="F#" Value="member this.Item(int) : Microsoft.Azure.CosmosDB.Table.TableOperation with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">取得または設定する位置のインデックス、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />項目。</param>
        <summary>
            取得または設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />指定したインデックス位置にある項目。
            </summary>
        <value><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />指定したインデックス位置にある項目。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public void Merge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Merge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Merge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Merge (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Merge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Merge entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">内容がマージされるエンティティです。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブル内の既存のエンティティで指定されたエンティティの内容とマージします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.Azure.CosmosDB.Table.TableOperation item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class Microsoft.Azure.CosmosDB.Table.TableOperation item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Remove(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As TableOperation) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; bool&#xA;override this.Remove : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; bool" Usage="tableBatchOperation.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />削除する項目。</param>
        <summary>
            指定された削除<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />項目を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。
            </summary>
        <returns>
          <c>true</c>場合は、項目が正常に削除されました。<c>false</c>、それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="tableBatchOperation.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">インデックス、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />から削除する、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。</param>
        <summary>
            削除、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />から指定したインデックス位置、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public void Replace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Replace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Replace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Replace (entity As ITableEntity)" />
      <MemberSignature Language="F#" Value="member this.Replace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; unit" Usage="tableBatchOperation.Replace entity" />
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
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">内容が置き換えられるエンティティです。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブル内の指定されたエンティティの内容を置き換えます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve">
      <MemberSignature Language="C#" Value="public void Retrieve (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Retrieve(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string -&gt; unit" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey)" />
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
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">取得するエンティティのパーティション キーを含む文字列。</param>
        <param name="rowKey">取得するエンティティの行キーを含む文字列。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />指定されたパーティション キーと行キーを持つエンティティを取得します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public void Retrieve&lt;TElement&gt; (string partitionKey, string rowKey, System.Collections.Generic.List&lt;string&gt; selectedColumns = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntity;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve&lt;(class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(string partitionKey, string rowKey, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Retrieve``1(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve(Of TElement As ITableEntity) (partitionKey As String, rowKey As String, Optional selectedColumns As List(Of String) = null)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; unit (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity)" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">取得するエンティティの型のクラスです。</typeparam>
        <param name="partitionKey">取得するエンティティのパーティション キーを含む文字列。</param>
        <param name="rowKey">取得するエンティティの行キーを含む文字列。</param>
        <param name="selectedColumns">投影の列名の一覧です。</param>
        <summary>
            挿入、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />行キーとパーティション キーに基づきエンティティを取得するバッチにします。 指定されたクラス型を拡張するものにエンティティを逆シリアル化されます<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public void Retrieve&lt;TResult&gt; (string partitionKey, string rowKey, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retrieve&lt;TResult&gt;(string partitionKey, string rowKey, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.Retrieve``1(System.String,System.String,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retrieve(Of TResult) (partitionKey As String, rowKey As String, resolver As EntityResolver(Of TResult), Optional selectedColumns As List(Of String) = null)" />
      <MemberSignature Language="F#" Value="member this.Retrieve : string * string * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * System.Collections.Generic.List&lt;string&gt; -&gt; unit" Usage="tableBatchOperation.Retrieve (partitionKey, rowKey, resolver, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">戻り値の型を指定した<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />に指定されたエンティティを解決します。</typeparam>
        <param name="partitionKey">取得するエンティティのパーティション キーを含む文字列。</param>
        <param name="rowKey">取得するエンティティの行キーを含む文字列。</param>
        <param name="resolver"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果内の特定の型として取得するエンティティを射影する実装。</param>
        <param name="selectedColumns">投影の列名の一覧です。</param>
        <summary>
            指定されたパーティション キーとバッチ操作に行キーを持つ指定したクラス型のエンティティを取得するテーブル操作を追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableBatchOperation.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Collections.IEnumerator" /> を返します。
            </summary>
        <returns><see cref="T:System.Collections.IEnumerator" /> の <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>