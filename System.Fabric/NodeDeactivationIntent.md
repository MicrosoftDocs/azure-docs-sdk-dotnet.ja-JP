<Type Name="NodeDeactivationIntent" FullName="System.Fabric.NodeDeactivationIntent">
  <TypeSignature Language="C#" Value="public enum NodeDeactivationIntent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeDeactivationIntent extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeDeactivationIntent" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeDeactivationIntent" />
  <TypeSignature Language="F#" Value="type NodeDeactivationIntent = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>なぜ、ノードが非アクティブに理由を説明します。</para>
    </summary>
    <remarks>
      <para>
                <see cref="T:System.Fabric.NodeDeactivationIntent" />列挙型がの一部として提供される、<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" />メソッドです。 </para>
      <para>
                Service Fabric では、この情報を使用して、ノードの正常なシャット ダウンを提供するノードに適切なアクションを実行します。 インテントは、一般的な進行または重要度があります。 </para>
      <para>
                1 つのインテントを指定して起動し、非アクティブ化は、後続の上位レベルのインテントを増やすことができます。 この進行の一般的な順序は、: 一時停止、再開、停止、強制停止です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>非アクティブ化インテントが無効であることを示します。 この値は使用されません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pause">
      <MemberSignature Language="C#" Value="Pause" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Pause = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberSignature Language="VB.NET" Value="Pause" />
      <MemberSignature Language="F#" Value="Pause = 1" Usage="System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>ノードを一時停止することを示します。 </para>
        </summary>
        <remarks>
          <para>
                この目的は、使用すると、Service Fabric は、指定したノードを変更できなくなります。 新しいレプリカが、ノードに配置されないと、既存のレプリカの移動またはシャット ダウンされていません。</para>
          <para>
                <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />目的は、1 つの場合に便利ですまたはノード上の複数のレプリカの問題が発生し、そのノードでは、詳しい調査のために分離</para>
          <para> 
                この調査では、ローカル ログを確認することを許可をメモリ ダンプを取得し、その他の情報を確認するには、このようなアクティビティを調査するために、リモート コンピューターへのアクセスなどがあります。 </para>
          <para>
                このモードの目的は、エラーが発生したときに存在していた同じ条件で追加のデバッグを実行できるように、ノードを保持しようとします。</para>
          <para>
                このモードを指定することは保証されませんノードにすべての変更を防止できますに注意してください。 </para>
          <para>
                たとえば、ノードを一時停止することを目的の受信後に、ノード上のレプリカがクラッシュする可能性があります。 </para>
          <para>
                別の例として、クラスター内の別の場所で発生した障害は、プライマリ レプリカに昇格するノードで、セカンダリ レプリカ可能性があります。</para>
          <para>
                このモードでは、Service Fabric が無効になる配置とリソースのバランスのターゲット ノード上</para>
          <para>
                さらに安全性チェックが (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) Service Fabric によって実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveData">
      <MemberSignature Language="C#" Value="RemoveData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberSignature Language="VB.NET" Value="RemoveData" />
      <MemberSignature Language="F#" Value="RemoveData = 3" Usage="System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>その目的は、ノードを再イメージ化することを示します。 Service Fabric にノード再イメージ化できません - この操作は Service Fabric の外部で行われます。</para>
        </summary>
        <remarks>
          <para>
                Service Fabric 受信すると、この目的としたことを確認します。 </para>
          <para>
                このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。 さらに、Service Fabric は、次のアクションを受け取ります。 </para>
          <para>
                配置とリソースのターゲット ノードで負荷分散を無効にします。</para>
          <para>
                すべてのノードからのレプリカを移動します。 </para>
          <para>
                ステートレスなインスタンスのつまり、別のノードに別のインスタンスを作成します。</para>
          <para>
                ステートフル サービス レプリカ置換レプリカがビルドされた別のノード (クラスターのための十分な容量がある) 場合</para>
          <para>
                パーティションの他のアクティブなセカンダリの交換を作成する前に、プライマリが行われます、レプリカがプライマリである場合は、</para>
          <para>
                ノードでのステートフルなレプリカは、状態をクリーンアップして終了する通知を受信します。</para>
          <para>
                データなしのこのノードを取得した結果としてが失われることができます発生ように安全性チェックのサブセットを実行します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="RemoveNode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveNode = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberSignature Language="VB.NET" Value="RemoveNode" />
      <MemberSignature Language="F#" Value="RemoveNode = 4" Usage="System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>ノードを返す必要はありませんが廃止されていることを示します。 Service Fabric は、ノードを停止できません - この操作は Service Fabric の外部で行われます。</para>
        </summary>
        <remarks>
          <para>
                Service Fabric 受信すると、この目的としたことを確認します。 </para>
          <para>
                このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。 さらに、Service Fabric は、次のアクションを受け取ります。 </para>
          <para>
                配置とリソースのターゲット ノードで負荷分散を無効にします。</para>
          <para>
                すべてのノードからのレプリカを移動します。 </para>
          <para>
                ステートレスなインスタンスのつまり、別のノードに別のインスタンスを作成します。</para>
          <para>
                ステートフル サービス レプリカ置換レプリカがビルドされた別のノード (クラスターのための十分な容量がある) 場合</para>
          <para>
                パーティションの他のアクティブなセカンダリの交換を作成する前に、プライマリが行われます、レプリカがプライマリである場合は、</para>
          <para>
                ノードでのステートフルなレプリカは、状態をクリーンアップして終了する通知を受信します。</para>
          <para>
                データなしのこのノードを取得した結果としてが失われることができます発生ように安全性チェックのサブセットを実行します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="Restart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Restart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberSignature Language="VB.NET" Value="Restart" />
      <MemberSignature Language="F#" Value="Restart = 2" Usage="System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>ノードを短時間の後に再起動するインテントであることを示します。 Service Fabric は、ノードを再起動できません - この操作は Service Fabric の外部で行われます。</para>
        </summary>
        <remarks>
          <para>
                ノードがシャット ダウンするなど、OS 更新プログラムまたは Service Fabric コードの更新を実行します。 </para>
          <para>
                このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。 さらに、Service Fabric は、次のアクションを受け取ります。 </para>
          <para>
                配置とリソースのターゲット ノードで負荷分散を無効にします。</para>
          <para>
                安全性チェックを実行します。 <see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />この目的の安全性チェックは実行されません。 </para>
          <para>
                すべてのレプリカと、ノードで実行されているインスタンスを閉じます。</para>
          <para>
                注: レプリカとインスタンスが閉じられると、Service Fabric は事後対応的作成ステートフル揮発性サービスとステートレス サービスのレプリカを置換します。 </para>
          <para>
                新しいレプリカは、Persisted レプリカ ノード上で<b>いない</b>という意図がこのノードを再起動して、再起動後に永続的な状態を回復するために構築します。 ノードがアクティブになると、レプリカが開かれます。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>