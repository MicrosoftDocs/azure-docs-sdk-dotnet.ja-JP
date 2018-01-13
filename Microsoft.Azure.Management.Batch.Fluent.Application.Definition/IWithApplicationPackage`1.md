<Type Name="IWithApplicationPackage&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithApplicationPackage&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplicationPackage`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplicationPackage(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithApplicationPackage&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親バッチ アカウント定義の段階です。</typeparam>
    <summary>
            アプリケーション パッケージの作成を許可するバッチ アプリケーション定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplicationPackage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt; DefineNewApplicationPackage (string applicationPackageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach`1&lt;!ParentT&gt; DefineNewApplicationPackage(string applicationPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithApplicationPackage`1.DefineNewApplicationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplicationPackage (applicationPackageName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplicationPackage : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithApplicationPackage.DefineNewApplicationPackage applicationPackageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationPackageName">アプリケーションのバージョン。</param>
        <summary>
            Batch アカウントのアプリケーションで新しいアプリケーション パッケージの定義の最初の段階です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>