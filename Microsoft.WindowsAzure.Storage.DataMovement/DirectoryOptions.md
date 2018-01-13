<Type Name="DirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions">
  <TypeSignature Language="C#" Value="public class DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DirectoryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DirectoryOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ディレクトリの転送操作で指定できるオプションのセットを表します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public bool Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.Recursive : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはディレクトリの転送処理を実行するときにサブディレクトリを含めるかどうかを示すブール値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchPattern">
      <MemberSignature Language="C#" Value="public string SearchPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchPattern As String" />
      <MemberSignature Language="F#" Value="member this.SearchPattern : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルの名前と照合するために使用する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            別のソース ディレクトリの型と再帰的に設定しない一致の動作が異なります: しないは標準のワイルドカードとしてソース ファイルの名前と照合ソースがローカル ディレクトリ パスの場合。 Recuresive が false に設定されている場合は、ソース ディレクトリの直下にあるファイルのみが一致します。 それ以外の場合も、サブディレクトリ内のすべてのファイルに照合します。
            
            Recuresive があり、true に設定されている場合に、ソースが Azure blob ディレクトリが場合は、名のプレフィックスとしてコピー元 blob と照合されます。
            それ以外の場合、Azure のみの blob がありで指定された正確な名前が一致します。
            
            再帰があり、true に設定されている場合に、ソースが Azure のファイルのディレクトリが場合はサポートされていません。 それ以外の場合ありで指定された正確な名前を持つ Azure のみのファイルが検索します。
            
            しないが指定されていない場合"*.*"Azure の blob またはファイルのディレクトリに空の文字列の中にソースをローカル ディレクトリに使用されます。 ようにしてください。 検索パターンを指定するか、再帰的な場合に true に設定ソースが Azure blob またはファイルのディレクトリ、それ以外の場合、blob/ファイルは照合されません。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>