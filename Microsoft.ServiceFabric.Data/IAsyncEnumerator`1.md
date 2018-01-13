<Type Name="IAsyncEnumerator&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IAsyncEnumerator&lt;out T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAsyncEnumerator`1&lt;+ T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAsyncEnumerator(Of Out T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IAsyncEnumerator&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>Covariant</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">列挙するオブジェクトの型。</typeparam>
    <summary>
            非同期の列挙子。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Current">
      <MemberSignature Language="C#" Value="public T Current { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Current" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.Current" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Current As T" />
      <MemberSignature Language="F#" Value="member this.Current : 'T" Usage="Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;'T&gt;.Current" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙子の現在の要素を取得します。
            </summary>
        <value>
            列挙子の現在の要素。
            </value>
        <remarks>To be added.</remarks>
        <remark>
            後に呼び出す<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" />が渡されるコレクションの末尾が未定義の動作と見なされます。
            </remark>
      </Docs>
    </Member>
    <Member MemberName="MoveNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; MoveNextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; MoveNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iAsyncEnumerator.MoveNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            列挙子の次の要素に列挙子を進めます。
            </summary>
        <returns>
            列挙子が次の要素に正常に進んだ場合は true。列挙子がコレクションの末尾を越えた場合は false。
             </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">コレクションは、列挙子の作成後に変更されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public void Reset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reset() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.Reset" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reset ()" />
      <MemberSignature Language="F#" Value="abstract member Reset : unit -&gt; unit" Usage="iAsyncEnumerator.Reset " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            列挙子を初期位置、つまりコレクションの最初の要素の前に設定します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">コレクションは、列挙子の作成後に変更されました。</exception>
      </Docs>
    </Member>
  </Members>
</Type>