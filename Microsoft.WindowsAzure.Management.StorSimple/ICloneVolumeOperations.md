<Type Name="ICloneVolumeOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations">
  <TypeSignature Language="C#" Value="public interface ICloneVolumeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICloneVolumeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICloneVolumeOperations" />
  <TypeSignature Language="F#" Value="type ICloneVolumeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            CloneVolume に関連するすべての操作 (詳細については http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.TriggerAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="iCloneVolumeOperations.TriggerAsync (sourceDeviceId, triggerCloneRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceDeviceId">
            どのクローンからソース デバイスの識別子がトリガーされます。
            </param>
        <param name="triggerCloneRequest">
            複製操作に必要なパラメーター
            </param>
        <param name="customRequestHeaders">
            カスタムの要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Backup 要素を複製します。
            </summary>
        <returns>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>