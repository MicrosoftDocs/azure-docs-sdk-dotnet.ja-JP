<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ アカウントを指定できるように仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount">既存のストレージ アカウント。</param>
        <summary>
            VM の状態に既存のストレージ アカウントを指定します。 OS とデータ ディスクの VHD にします。
            Marketplace、またはユーザー イメージ (一般化されたイメージ) に基づく OS ディスクは、このストレージ アカウントに保存されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (creatable As ICreatable(Of IStorageAccount)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">作成可能なストレージ アカウント定義します。</param>
        <summary>
            VM の OS とデータを格納する not をまだ作成のストレージ アカウントの定義を指定に Vhd をディスクです。
            Marketplace イメージを基に、OS ディスクだけは、新しいストレージ アカウントに保存されます。
            ユーザー イメージを基に OS ディスクは、ユーザー イメージと同じストレージ アカウントに格納されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewStorageAccount(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しいストレージ アカウントの名前。</param>
        <summary>
            VM の OS とデータを格納する新しいストレージ アカウントの名前を指定に VHD をディスクです。
            Marketplace イメージを基に、OS ディスクだけは、新しいストレージ アカウントに保存されます。
            ユーザー イメージを基に OS ディスクは、ユーザー イメージと同じストレージ アカウントに格納されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>