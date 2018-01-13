<Type Name="NodeFile" FullName="Microsoft.Azure.Batch.NodeFile">
  <TypeSignature Language="C#" Value="public abstract class NodeFile : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NodeFile extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NodeFile" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NodeFile&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type NodeFile = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ノードまたはタスクからファイルにアクセスするメソッドとプロパティを公開します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyToStream">
      <MemberSignature Language="C#" Value="public virtual void CopyToStream (System.IO.Stream stream, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyToStream(class System.IO.Stream stream, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member CopyToStream : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.CopyToStream : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.CopyToStream (stream, byteRange, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="stream">ファイルの内容がコピー先のストリーム。</param>
        <param name="byteRange">取得するファイルのバイトの範囲です。 Null の場合、ファイル全体が取得されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            ファイルの内容を指定したストリームにコピーへの呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyToStreamAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CopyToStreamAsync (System.IO.Stream stream, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CopyToStreamAsync(class System.IO.Stream stream, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CopyToStreamAsync : System.IO.Stream * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.CopyToStreamAsync (stream, byteRange, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stream">ファイルの内容がコピー先のストリーム。</param>
        <param name="byteRange">取得するファイルのバイトの範囲です。 Null の場合、ファイル全体が取得されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ファイルの内容を指定したストリームにコピーへの非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.NodeFile" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.Delete(System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Delete (Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Delete : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.Delete (recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            ファイルを削除する呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.DeleteAsync(System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.DeleteAsync (recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ファイルを削除する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.IsDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDirectory : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Batch.NodeFile.IsDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルがディレクトリであるかどうかを示す値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.NodeFile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete as of 02/2017. Use Path instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Batch.NodeFile.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルのパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.FileProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.FileProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Batch.FileProperties" Usage="Microsoft.Azure.Batch.NodeFile.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.FileProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルの FileProperties を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsString">
      <MemberSignature Language="C#" Value="public string ReadAsString (System.Text.Encoding encoding = null, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ReadAsString(class System.Text.Encoding encoding, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.ReadAsString(System.Text.Encoding,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ReadAsString : System.Text.Encoding * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; string" Usage="nodeFile.ReadAsString (encoding, byteRange, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="encoding">ファイル データの解釈に使用するエンコーディングします。 値または null が指定されていない場合は、UTF8 が使用されます。</param>
        <param name="byteRange">取得するファイルのバイトの範囲です。 Null の場合、ファイル全体が取得されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            文字列として、ファイルの内容を返すへの呼び出しをブロックしています。
            </summary>
        <returns>ファイルの内容を含む文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsStringAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ReadAsStringAsync (System.Text.Encoding encoding = null, Microsoft.Azure.Batch.GetFileRequestByteRange byteRange = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; ReadAsStringAsync(class System.Text.Encoding encoding, class Microsoft.Azure.Batch.GetFileRequestByteRange byteRange, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.ReadAsStringAsync(System.Text.Encoding,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReadAsStringAsync : System.Text.Encoding * Microsoft.Azure.Batch.GetFileRequestByteRange * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="nodeFile.ReadAsStringAsync (encoding, byteRange, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.NodeFile/&lt;ReadAsStringAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="byteRange" Type="Microsoft.Azure.Batch.GetFileRequestByteRange" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encoding">ファイル データの解釈に使用するエンコーディングします。 値または null が指定されていない場合は、UTF8 が使用されます。</param>
        <param name="byteRange">取得するファイルのバイトの範囲です。 Null の場合、ファイル全体が取得されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            文字列としてファイルの内容を返す非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public abstract void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="nodeFile.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。  詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.NodeFile.Name" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />です。</param>
        <summary>
            現在の更新<see cref="T:Microsoft.Azure.Batch.NodeFile" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NodeFile.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="nodeFile.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。  詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.NodeFile.Name" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.NodeFile.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在の更新<see cref="T:Microsoft.Azure.Batch.NodeFile" />です。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeFile.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.NodeFile.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>