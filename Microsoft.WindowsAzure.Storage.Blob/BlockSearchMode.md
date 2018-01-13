<Type Name="BlockSearchMode" FullName="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode">
  <TypeSignature Language="C#" Value="public enum BlockSearchMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BlockSearchMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum BlockSearchMode" />
  <TypeSignature Language="F#" Value="type BlockSearchMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            どのブロックの指定されたブロックを検索するリストを検索するかを示します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Committed">
      <MemberSignature Language="C#" Value="Committed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode Committed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Committed" />
      <MemberSignature Language="VB.NET" Value="Committed" />
      <MemberSignature Language="F#" Value="Committed = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Committed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            コミット後のブロック一覧のみを検索します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Latest">
      <MemberSignature Language="C#" Value="Latest" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode Latest = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Latest" />
      <MemberSignature Language="VB.NET" Value="Latest" />
      <MemberSignature Language="F#" Value="Latest = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Latest" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            最初に、コミット前のブロック一覧を検索し、ブロックが見つからない場合があります、コミットされたブロック リストを検索します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Uncommitted">
      <MemberSignature Language="C#" Value="Uncommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode Uncommitted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Uncommitted" />
      <MemberSignature Language="VB.NET" Value="Uncommitted" />
      <MemberSignature Language="F#" Value="Uncommitted = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode.Uncommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            コミット前のブロック一覧のみを検索します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>