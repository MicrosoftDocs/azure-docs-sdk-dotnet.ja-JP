<Type Name="FaultType" FullName="System.Fabric.FaultType">
  <TypeSignature Language="C#" Value="public enum FaultType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FaultType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FaultType" />
  <TypeSignature Language="VB.NET" Value="Public Enum FaultType" />
  <TypeSignature Language="F#" Value="type FaultType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>サービスを報告するエラーの種類を示します: 無効な一時的または永続的です。 </para>
    </summary>
    <remarks>
      <para>サービスを使用して実行時にエラーを報告することができます、<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />フォールトの種類を指定します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.FaultType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>型が正しくありません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Permanent">
      <MemberSignature Language="C#" Value="Permanent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Permanent = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Permanent" />
      <MemberSignature Language="VB.NET" Value="Permanent" />
      <MemberSignature Language="F#" Value="Permanent = 1" Usage="System.Fabric.FaultType.Permanent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>永続的な障害は、レプリカがから回復できないエラーです。 この種類のエラーは、こと、レプリカでも、さらに進行状況とを削除して交換を示します。 </para>
        </summary>
        <remarks>
          <para>永続的な障害の例は、情報をディスクに書き込もうし、ディスクが削除されていたか、使用可能なできなかったことを決定する永続的なステートフルなサービスになります。 呼び出す<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />経由で中止となるサービスに永続的な障害の結果を報告し、 <languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /> または<languageKeyword>IStatelessServiceInstance です。</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /> 状態または完了操作を正常にクリーンアップする可能性です。 したがって、クリーンアップまたはその他の実行時間の長い作業が必要な場合が実行する前に<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />と呼びます。 永続的なと一時的な障害の違いには、ステートフルなサービスの永続的なことに注意してください。 呼び出しシーケンス以外の他のサービスの種類に与える影響については、同じ: レプリカまたはインスタンスが削除される、そのレプリカまたはインスタンスですべての状態は失われ、レプリカまたはインスタンスを再作成する可能性のある別の場所にします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Transient">
      <MemberSignature Language="C#" Value="Transient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Transient = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Transient" />
      <MemberSignature Language="VB.NET" Value="Transient" />
      <MemberSignature Language="F#" Value="Transient = 2" Usage="System.Fabric.FaultType.Transient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>一時的なエラーは、一時的な状態が原因で進行状況の詳細と、他のユーザーの要求を処理から、レプリカがあることを示します。 </para>
        </summary>
        <remarks>
          <para>一時的なエラーの例は、サービスの状態またはいくつかの参照ファイルの一部が破損していますが、サービスが再初期化するされたときに修復できることを決定します。 この場合、サービスを使用して、<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />に一時的なエラーを報告するメソッド。 経由でサービスを閉じる一時的なエラーを報告<languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /> または<languageKeyword>IStatelessServiceInstance</languageKeyword> 。<see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />. ステートレスおよびステートフルなサービスのことに注意してください、揮発性の一時的なエラーは、エラー状態は維持されませんので非常に便利です。 これらのサービスでは、一時的または永続的なエラーを使用するかどうかは、サービスを正常にクリーンアップを非同期的に終了または異常終了されており、同期するかどうかに依存<languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /> または<languageKeyword>IStatelessServiceInstance です。</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /> メソッドをオーバーライドします。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>