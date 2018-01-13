<Type Name="TransferConfigurations" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations">
  <TypeSignature Language="C#" Value="public class TransferConfigurations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferConfigurations extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferConfigurations" />
  <TypeSignature Language="F#" Value="type TransferConfigurations = class" />
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
            TransferConfigurations クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockSize">
      <MemberSignature Language="C#" Value="public int BlockSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BlockSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockSize As Integer" />
      <MemberSignature Language="F#" Value="member this.BlockSize : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送に使用する Windows Azure ストレージれる blob をブロックするブロック サイズを設定します。 4 MB ~ 100 MB にするおよび倍数である必要がありますは 4 MB です。
            
            現時点では、ブロック blob の最大ブロック数は、50000 に制限されます。
            転送サイズの大きなファイルおよび指定されたブロック サイズより小さい場合の最小値 (サイズ/50000) がありますにリセットされますは、最小値および複数より大きい値はこのファイルの 4 MB です。
            </summary>
        <value>Windows Azure ストレージの転送に使用するブロック サイズを指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperations">
      <MemberSignature Language="C#" Value="public int ParallelOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ParallelOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperations As Integer" />
      <MemberSignature Language="F#" Value="member this.ParallelOperations : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定数の作業を示す値の項目を同時に処理します。 ダウンロードや、単一の blob のアップロードは、大量の作業項目で構成できます。
            </summary>
        <value>同時に処理する作業項目の数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentPrefix">
      <MemberSignature Language="C#" Value="public string UserAgentPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentPrefix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentPrefix : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
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
            取得またはユーザー エージェントのプレフィックスの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>