<Type Name="NameValidator" FullName="Microsoft.WindowsAzure.Storage.NameValidator">
  <TypeSignature Language="C#" Value="public static class NameValidator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NameValidator extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.NameValidator" />
  <TypeSignature Language="VB.NET" Value="Public Class NameValidator" />
  <TypeSignature Language="F#" Value="type NameValidator = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Microsoft Azure ストレージ サービスでリソース名を検証するヘルパーを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ValidateBlobName">
      <MemberSignature Language="C#" Value="public static void ValidateBlobName (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateBlobName(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateBlobName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateBlobName (blobName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateBlobName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateBlobName blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName">検証対象の blob 名を表す文字列。</param>
        <summary>
            Blob 名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateContainerName">
      <MemberSignature Language="C#" Value="public static void ValidateContainerName (string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateContainerName(string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateContainerName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateContainerName (containerName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateContainerName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateContainerName containerName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerName">検証対象のコンテナー名を表す文字列。</param>
        <summary>
            コンテナー名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateDirectoryName">
      <MemberSignature Language="C#" Value="public static void ValidateDirectoryName (string directoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateDirectoryName(string directoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateDirectoryName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateDirectoryName (directoryName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateDirectoryName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateDirectoryName directoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="directoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="directoryName">検証するディレクトリ名を表す文字列。</param>
        <summary>
            ディレクトリ名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateFileName">
      <MemberSignature Language="C#" Value="public static void ValidateFileName (string fileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateFileName(string fileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateFileName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateFileName (fileName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateFileName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateFileName fileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fileName">検証対象のファイル名を表す文字列。</param>
        <summary>
            ファイル名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateQueueName">
      <MemberSignature Language="C#" Value="public static void ValidateQueueName (string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateQueueName(string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateQueueName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateQueueName (queueName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateQueueName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateQueueName queueName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queueName">検証対象のキュー名を表す文字列。</param>
        <summary>
            キュー名は有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateShareName">
      <MemberSignature Language="C#" Value="public static void ValidateShareName (string shareName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateShareName(string shareName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateShareName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateShareName (shareName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateShareName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateShareName shareName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shareName">検証対象の共有名を表す文字列。</param>
        <summary>
            共有名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateTableName">
      <MemberSignature Language="C#" Value="public static void ValidateTableName (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateTableName(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateTableName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateTableName (tableName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateTableName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateTableName tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">検証対象のテーブル名を表す文字列。</param>
        <summary>
            テーブル名が有効なかどうかを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>