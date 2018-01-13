<Type Name="AzureStorageAccess" FullName="Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess">
  <TypeSignature Language="C#" Value="public class AzureStorageAccess : Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageAccess extends System.Object implements class Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageAccess&#xA;Implements IStorageAccess" />
  <TypeSignature Language="F#" Value="type AzureStorageAccess = class&#xA;    interface IStorageAccess" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            HDInsight クラスターに対してジョブ操作のための記憶域アクセスの詳細を管理します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageAccess (string storageAccountName, string storageAccountKey, string defaultStorageContainer, string storageAccountSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountName, string storageAccountKey, string defaultStorageContainer, string storageAccountSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountName As String, storageAccountKey As String, defaultStorageContainer As String, Optional storageAccountSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess : string * string * string * string -&gt; Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess" Usage="new Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess (storageAccountName, storageAccountKey, defaultStorageContainer, storageAccountSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="storageAccountKey" Type="System.String" />
        <Parameter Name="defaultStorageContainer" Type="System.String" />
        <Parameter Name="storageAccountSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">
            必須。 ストレージ アカウント名。
            </param>
        <param name="storageAccountKey">
            必須。 ストレージ アカウント キー。
            </param>
        <param name="defaultStorageContainer">
            必須。 既定のストレージ コンテナー名。
            </param>
        <param name="storageAccountSuffix">
            省略可能。 ストレージ アカウントの URI のサフィックスです。 たとえば、"core.chinacloudapi.cn"とします。
            </param>
        <summary>
            AzureStorageAccess クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileContent">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetFileContent (string blobReferencePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetFileContent(string blobReferencePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.AzureStorageAccess.GetFileContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFileContent (blobReferencePath As String) As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetFileContent : string -&gt; System.IO.Stream&#xA;override this.GetFileContent : string -&gt; System.IO.Stream" Usage="azureStorageAccess.GetFileContent blobReferencePath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess.GetFileContent(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobReferencePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobReferencePath">
            必須。 Url を生成するための blob 参照パス。
            </param>
        <summary>
            Blob 参照のパスからファイルの内容を取得します。
            </summary>
        <returns>
            入力 blob 参照パスのファイルの内容。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>