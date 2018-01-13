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
            <span data-ttu-id="80cd5-101">Service Fabric のアクティベーション コンテキストを表しますには、サービスがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="80cd5-101">Represents activation context for the Service Fabric activated service.</span></span>
            </summary>
    <remarks><span data-ttu-id="80cd5-102">サービス マニフェストからの情報と作業のように、現在アクティブ化されたコード パッケージに関する情報を含むディレクトリ、コンテキスト id などです。</span><span class="sxs-lookup"><span data-stu-id="80cd5-102">Includes information from the service manifest as well as information about the currently activated code package like work directory, context id etc.</span></span></remarks>
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
            <span data-ttu-id="80cd5-103">名前"logicalDirectoryName"を使用して作業ディレクトリ内のサブディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="80cd5-103">Retrieves the path to sub directory inside the work directory with the name "logicalDirectoryName".</span></span>
            </summary>
        <returns><span data-ttu-id="80cd5-104">作業ディレクトリ内の名前 logicalDirectoryName でサブ ディレクトリへのパス</span><span class="sxs-lookup"><span data-stu-id="80cd5-104">The path to sub directory with name logicalDirectoryName inside work directory</span></span></returns>
        <remarks><span data-ttu-id="80cd5-105">作業ディレクトリの下で logicalDirectoryName が見つからない場合は、例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="80cd5-105">Throws an exception if logicalDirectoryName is not found under work directory.</span></span>
            <span data-ttu-id="80cd5-106">それ以外の場合は ClusterManifest LogicalDirectories セクション名で指定されたディレクトリへのシンボリック リンクである WorkDirectory\logicalDirectoryName のディレクトリ パスを返します。</span><span class="sxs-lookup"><span data-stu-id="80cd5-106">Otherwise will return directory path WorkDirectory\logicalDirectoryName which is a symbolic link to directory specified with Name under LogicalDirectories Section of ClusterManifest.</span></span>
            <span data-ttu-id="80cd5-107">例: 指定した場合に<LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" />ディレクトリ名"Foo"では、このメソッドの呼び出しが WorkDirectory\Foo のパスを返すとします。</span><span class="sxs-lookup"><span data-stu-id="80cd5-107">for example: if you have specified <LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" /> and call to this method with directoryName "Foo" will return you path WorkDirectory\Foo.</span></span> <span data-ttu-id="80cd5-108">加えられたすべての書き込みには、パスは D:\Foo\NodeId\ApplicationType_ApplicationVersion に移動する が返されます。</span><span class="sxs-lookup"><span data-stu-id="80cd5-108">Any writes made to returned path will go to D:\Foo\NodeId\ApplicationType_ApplicationVersion.</span></span>
            <span data-ttu-id="80cd5-109">このメソッドは、ディレクトリ名 foo と答えた場合でもまだ戻るディレクトリ パス WorkDirectory\Foo ように大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="80cd5-109">This method is case insensitive so even if you say directoryName foo it will still return you directory path WorkDirectory\Foo.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>