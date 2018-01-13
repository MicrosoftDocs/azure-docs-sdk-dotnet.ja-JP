<Type Name="IKeyResolver" FullName="Microsoft.Azure.KeyVault.Core.IKeyResolver">
  <TypeSignature Language="C#" Value="public interface IKeyResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKeyResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Core.IKeyResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKeyResolver" />
  <TypeSignature Language="F#" Value="type IKeyResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            キーの競合回避モジュールのインターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt; ResolveKeyAsync (string kid, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Core.IKey&gt; ResolveKeyAsync(string kid, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKeyResolver.ResolveKeyAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveKeyAsync (kid As String, token As CancellationToken) As Task(Of IKey)" />
      <MemberSignature Language="F#" Value="abstract member ResolveKeyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt;" Usage="iKeyResolver.ResolveKeyAsync (kid, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Core.IKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kid">キーの id を解決するには</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定したキー識別子の IKey 実装を提供します。
            </summary>
        <returns>解決済みの IKey 実装または null</returns>
        <remarks>実装では、認識されていることを確認する kid の形式を確認する必要があります。 キーの競合回避モジュールのチェーンを有効にするキー識別子の認識されない例外ではなく、null の場合が返されます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>