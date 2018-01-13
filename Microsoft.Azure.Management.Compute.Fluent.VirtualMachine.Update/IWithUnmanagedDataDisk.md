<Type Name="IWithUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUnmanagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithUnmanagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アンマネージ データ ディスクの構成を指定できるように仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.DefineUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineUnmanagedDataDisk (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" Usage="iWithUnmanagedDataDisk.DefineUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ディスクの名前。</param>
        <summary>
            その構成、仮想マシンに接続する空のアンマネージ データ ディスクの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.UpdateUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithUnmanagedDataDisk.UpdateUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">既存のディスクの名前。</param>
        <summary>
            このバーチャル マシンの既存のアンマネージ データ ディスクの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>データ ディスクの更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingUnmanagedDataDisk (storageAccountName As String, containerName As String, vhdName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingUnmanagedDataDisk : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">ストレージ アカウント名。</param>
        <param name="containerName">VHD ファイルを保持するコンテナーの名前。</param>
        <param name="vhdName">VHD ファイルの名前。</param>
        <summary>
            データ ディスクとして仮想マシンにアタッチする必要がある既存の VHD を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VM の作成可能な定義を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithNewUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewUnmanagedDataDisk (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithNewUnmanagedDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">GB のディスク サイズです。</param>
        <summary>
            新しい空白のアンマネージ データ ディスクを仮想マシンに接続する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VM の作成可能な定義を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun">削除するデータ ディスクの論理ユニット番号。</param>
        <summary>
            バーチャル マシンからアンマネージ データ ディスクをデタッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除する既存のデータ ディスクの名前。</param>
        <summary>
            バーチャル マシンから、アンマネージ データ ディスクをデタッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>