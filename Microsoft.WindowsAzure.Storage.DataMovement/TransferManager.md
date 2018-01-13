<Type Name="TransferManager" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager">
  <TypeSignature Language="C#" Value="public static class TransferManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed TransferManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferManager" />
  <TypeSignature Language="F#" Value="type TransferManager = class" />
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
            TransferManager クラス
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Configurations">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations Configurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations Configurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.Configurations" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Configurations As TransferConfigurations" />
      <MemberSignature Language="F#" Value="member this.Configurations : Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.Configurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送の転送マネージャーに関連付けられている構成の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure の 1 つのメタデータを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure のメタデータは、Azure のファイルを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            Azure blob にコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            別のコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destBlob As CloudBlob, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            指定した URI からファイルを Azure blob にコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure blob を同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destFile As CloudFile, isServiceCopy As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <summary>
            指定した URI からファイルを Azure のファイルにコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure ファイルを同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure の 1 つのメタデータを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceBlob As CloudBlob, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure のメタデータは、Azure のファイルを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure blob にコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceFile As CloudFile, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            別のコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destBlob As CloudBlob, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定した URI からファイルを Azure blob にコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure blob を同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyAsync (sourceUri As Uri, destFile As CloudFile, isServiceCopy As Boolean, options As CopyOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定した URI からファイルを Azure のファイルにコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure ファイルを同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure の 1 つのメタデータを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceBlob, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            コピーのコンテンツ、プロパティ、および Azure のメタデータは、Azure のファイルを blob です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure blob にコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceFile, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            別のコンテンツ、プロパティ、および Azure のファイルのメタデータをコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destBlob, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            指定した URI からファイルを Azure blob にコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure blob を同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CopyAsync (Uri sourceUri, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CopyAsync(class System.Uri sourceUri, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.File.CloudFile,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyAsync : Uri * Microsoft.WindowsAzure.Storage.File.CloudFile * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyAsync (sourceUri, destFile, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceUri" Type="System.Uri" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceUri"><see cref="T:System.Uri" />のソース ファイルです。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            指定した URI からファイルを Azure のファイルにコピーします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>Azure ファイルを同期的に、URI からコピーがまだサポートされていません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destBlobDir As CloudBlobDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destBlobDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを別の Azure blob ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destFileDir As CloudFileDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destFileDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを Azure のファイル ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceFileDir As CloudFileDirectory, destBlobDir As CloudBlobDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destBlobDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure ファイル ディレクトリを Azure blob ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CopyDirectoryAsync (sourceFileDir As CloudFileDirectory, destFileDir As CloudFileDirectory, isServiceCopy As Boolean, options As CopyDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destFileDir, isServiceCopy, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure ファイル ディレクトリを別の Azure のファイル ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destBlobDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを別の Azure blob ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceBlobDir, destFileDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを Azure のファイル ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destBlobDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure ファイル ディレクトリを Azure blob ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; CopyDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, bool isServiceCopy, class Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.Boolean,Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CopyDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * bool * Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.CopyDirectoryAsync (sourceFileDir, destFileDir, isServiceCopy, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="isServiceCopy" Type="System.Boolean" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="isServiceCopy">コピーがサービス側の非同期コピーであるかどうかを示すフラグです。
            場合は true、サービス側の非同期のコピーをこのフラグが設定されている場合に使用されます。このフラグが false に設定されている場合、ファイルが最初に、ソースからダウンロードし、変換先にアップロードします。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure ファイル ディレクトリを別の Azure のファイル ディレクトリにコピーします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destStream As Stream) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destPath As String) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destStream As Stream) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destPath As String) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destStream As Stream, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceBlob As CloudBlob, destPath As String, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destStream As Stream, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadAsync (sourceFile As CloudFile, destPath As String, options As DownloadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destStream, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlob sourceBlob, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlob,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlob * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceBlob, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />ソース Azure blob はします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure の blob Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, System.IO.Stream destStream, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, class System.IO.Stream destStream, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.IO.Stream,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * System.IO.Stream * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destStream, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destStream">A<see cref="T:System.IO.Stream" />コピー先のストリームを表すオブジェクト。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DownloadAsync (Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DownloadAsync(class Microsoft.WindowsAzure.Storage.File.CloudFile sourceFile, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync(Microsoft.WindowsAzure.Storage.File.CloudFile,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadAsync : Microsoft.WindowsAzure.Storage.File.CloudFile * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadAsync (sourceFile, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイルのソースはします。</param>
        <param name="destPath">コピー先ファイルへのパス。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイルをダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadDirectoryAsync (sourceBlobDir As CloudBlobDirectory, destPath As String, options As DownloadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceBlobDir, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destPath">宛先ディレクトリへのパス</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DownloadDirectoryAsync (sourceFileDir As CloudFileDirectory, destPath As String, options As DownloadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceFileDir, destPath, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destPath">宛先ディレクトリへのパス</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイル ディレクトリをダウンロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory sourceBlobDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceBlobDir, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />ソース Azure blob ディレクトリはします。</param>
        <param name="destPath">宛先ディレクトリへのパス</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure blob ディレクトリを Azure Blob ストレージからダウンロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync (Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; DownloadDirectoryAsync(class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory sourceFileDir, string destPath, class Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync(Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,System.String,Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DownloadDirectoryAsync : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * string * Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.DownloadDirectoryAsync (sourceFileDir, destPath, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="destPath" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ソース Azure ファイルのディレクトリはします。</param>
        <param name="destPath">宛先ディレクトリへのパス</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure File Storage から Azure のファイル ディレクトリをダウンロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destBlob As CloudBlob) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destFile As CloudFile) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destBlob As CloudBlob) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destFile As CloudFile) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destBlob As CloudBlob, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourceStream As Stream, destFile As CloudFile, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destBlob As CloudBlob, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadAsync (sourcePath As String, destFile As CloudFile, options As UploadOptions, context As SingleTransferContext) As Task" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destBlob, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (System.IO.Stream sourceStream, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(class System.IO.Stream sourceStream, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourceStream, destFile, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceStream" Type="System.IO.Stream" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceStream">A<see cref="T:System.IO.Stream" />ファイルの内容を提供するオブジェクト。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlob destBlob, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlob,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlob * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destBlob, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlob" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destBlob"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />されるコピー先 Azure blob です。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure Blob ストレージにファイルをアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UploadAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFile destFile, Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UploadAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFile destFile, class Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFile,Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions,Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFile * Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions * Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadAsync (sourcePath, destFile, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="With TransferContext, it also accepts DirectoryTransferContext. Here forbid this behavior.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFile" Type="Microsoft.WindowsAzure.Storage.File.CloudFile" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ファイルへのパス。</param>
        <param name="destFile"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> Azure ファイル変換先はします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            Azure File Storage にアップロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destBlobDir As CloudBlobDirectory) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <summary>
            ディレクトリを Azure Blob ストレージにアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destFileDir As CloudFileDirectory) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <summary>
            ディレクトリを Azure File Storage にアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destBlobDir As CloudBlobDirectory, options As UploadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリを Azure Blob ストレージにアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UploadDirectoryAsync (sourcePath As String, destFileDir As CloudFileDirectory, options As UploadDirectoryOptions, context As DirectoryTransferContext) As Task(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir, options, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリを Azure File Storage にアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory destBlobDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destBlobDir, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destBlobDir" Type="Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destBlobDir"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />先 Azure blob ディレクトリはします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            ディレクトリを Azure Blob ストレージにアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadDirectoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync (string sourcePath, Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; UploadDirectoryAsync(string sourcePath, class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory destFileDir, class Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions options, class Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext context, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync(System.String,Microsoft.WindowsAzure.Storage.File.CloudFileDirectory,Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions,Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UploadDirectoryAsync : string * Microsoft.WindowsAzure.Storage.File.CloudFileDirectory * Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions * Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferManager.UploadDirectoryAsync (sourcePath, destFileDir, options, context, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destFileDir" Type="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourcePath">ソース ディレクトリへのパス</param>
        <param name="destFileDir"><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />先 Azure ファイルのディレクトリはします。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.UploadDirectoryOptions" />操作の追加オプションを指定するオブジェクト。</param>
        <param name="context">A<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />タスクの完了を待機しているときに監視するオブジェクト。</param>
        <summary>
            ディレクトリを Azure File Storage にアップロードします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>