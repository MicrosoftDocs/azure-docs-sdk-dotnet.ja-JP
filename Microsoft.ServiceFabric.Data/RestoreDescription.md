<Type Name="RestoreDescription" FullName="Microsoft.ServiceFabric.Data.RestoreDescription">
  <TypeSignature Language="C#" Value="public struct RestoreDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreDescription" />
  <TypeSignature Language="F#" Value="type RestoreDescription = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RestoreDescription には、すべてのステートフル サービス レプリカを復元するために必要な情報が含まれています。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupFolderPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription backupFolderPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできません、空または空白のみで構成されます。 UNC パスも指定することがあります。
            </param>
        <summary>
            新しいインスタンスを初期化、<cref name="RestoreDescription" />構造体
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String,Microsoft.ServiceFabric.Data.RestorePolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string * Microsoft.ServiceFabric.Data.RestorePolicy -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription (backupFolderPath, restorePolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできません、空または空白のみで構成されます。 UNC パスも指定することがあります。
            </param>
        <param name="restorePolicy">復元のポリシー。</param>
        <summary>
            RestoreDescription 構造体の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolderPath">
      <MemberSignature Language="C#" Value="public string BackupFolderPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolderPath : string" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリカの状態を復元するために使用するディレクトリを取得します。
            このパラメーターを null にすることはできません、空または空白のみで構成されます。 UNC パスも指定することがあります。
            </summary>
        <value>
            レプリカの状態を復元するために使用するディレクトリ。
            </value>
        <remarks>
            フォルダーには、完全バックアップを 1 つ以上含まれている必要があります。
            さらに、1 つまたは複数の増分バックアップを含めることできます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.RestorePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.RestorePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As RestorePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.ServiceFabric.Data.RestorePolicy" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            復元のポリシーを取得します。
            </summary>
        <value>
            復元操作に使用するポリシー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>