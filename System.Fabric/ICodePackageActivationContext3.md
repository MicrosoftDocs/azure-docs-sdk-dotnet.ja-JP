<Type Name="ICodePackageActivationContext3" FullName="System.Fabric.ICodePackageActivationContext3">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext3 : IDisposable, System.Fabric.ICodePackageActivationContext2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext3 implements class System.Fabric.ICodePackageActivationContext, class System.Fabric.ICodePackageActivationContext2, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext3" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext3&#xA;Implements ICodePackageActivationContext2, IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext3 = interface&#xA;    interface ICodePackageActivationContext2&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext2</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Service Fabric のアクティベーション コンテキストを表しますには、サービスがアクティブになります。
            </summary>
    <remarks>サービス マニフェストからの情報と作業のように、現在アクティブ化されたコード パッケージに関する情報を含むディレクトリ、コンテキスト id などです。</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext3.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetDirectory : string -&gt; string" Usage="iCodePackageActivationContext3.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            名前"logicalDirectoryName"を使用して作業ディレクトリ内のサブディレクトリへのパスを取得します。
            </summary>
        <returns>作業ディレクトリ内の名前 logicalDirectoryName でサブ ディレクトリへのパス</returns>
        <remarks>作業ディレクトリの下で logicalDirectoryName が見つからない場合は、例外をスローします。
            それ以外の場合は ClusterManifest LogicalDirectories セクション名で指定されたディレクトリへのシンボリック リンクである WorkDirectory\logicalDirectoryName のディレクトリ パスを返します。
            例: 指定した場合に<LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" />ディレクトリ名"Foo"では、このメソッドの呼び出しが WorkDirectory\Foo のパスを返すとします。 加えられたすべての書き込みには、パスは D:\Foo\NodeId\ApplicationType_ApplicationVersion に移動する が返されます。
            このメソッドは、ディレクトリ名 foo と答えた場合でもまだ戻るディレクトリ パス WorkDirectory\Foo ように大文字小文字を区別します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>