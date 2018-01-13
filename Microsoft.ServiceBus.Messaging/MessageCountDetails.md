<Type Name="MessageCountDetails" FullName="Microsoft.ServiceBus.Messaging.MessageCountDetails">
  <TypeSignature Language="C#" Value="public sealed class MessageCountDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageCountDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageCountDetails" />
  <TypeSignature Language="F#" Value="type MessageCountDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MessageCountDetails", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>このクラスには、プライマリのメッセージング エンティティ (キュー、トピック、サブスクリプション) のサブキューからメッセージの詳細を取得することができるようにするプロパティが含まれています。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails (long activeMessageCount, long deadletterMessageCount, long scheduledMessageCount, long transferMessageCount, long transferDlqMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 activeMessageCount, int64 deadletterMessageCount, int64 scheduledMessageCount, int64 transferMessageCount, int64 transferDlqMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activeMessageCount As Long, deadletterMessageCount As Long, scheduledMessageCount As Long, transferMessageCount As Long, transferDlqMessageCount As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessageCountDetails : int64 * int64 * int64 * int64 * int64 -&gt; Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="new Microsoft.ServiceBus.Messaging.MessageCountDetails (activeMessageCount, deadletterMessageCount, scheduledMessageCount, transferMessageCount, transferDlqMessageCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activeMessageCount" Type="System.Int64" />
        <Parameter Name="deadletterMessageCount" Type="System.Int64" />
        <Parameter Name="scheduledMessageCount" Type="System.Int64" />
        <Parameter Name="transferMessageCount" Type="System.Int64" />
        <Parameter Name="transferDlqMessageCount" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="activeMessageCount">アクティブなメッセージの数。</param>
        <param name="deadletterMessageCount">配信不能メッセージの数。</param>
        <param name="scheduledMessageCount">スケジュールされたメッセージの数。</param>
        <param name="transferMessageCount">メッセージの数は、その他のキュー、サブスクリプション、またはトピックに転送されます。</param>
        <param name="transferDlqMessageCount">メッセージの数は、配信不能キューに転送されます。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />アクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージ、メッセージの数を持つクラスが他のキュー、サブスクリプション、またはトピックに転送され、メッセージの数が配信不能キューに転送します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキュー、トピック、またはサブスクリプションのアクティブなメッセージの数を設定します。</summary>
        <value>返します<see cref="T:System.Int64" />アクティブなメッセージの数を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または配信不能メッセージのメッセージの数を設定します。</summary>
        <value>返します<see cref="T:System.Int64" />配信不能メッセージのメッセージの数を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65539)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または番号のスケジュールされたメッセージを設定します。</summary>
        <value>返します<see cref="T:System.Int64" />スケジュールされたメッセージの数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65541)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または数値に文字を配信不能に転送されるメッセージを設定します。</summary>
        <value>返します<see cref="T:System.Int64" />番号に文字を配信不能に転送されるメッセージを指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65540)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または別のキュー、トピック、またはサブスクリプションに転送されるメッセージの数を設定します。</summary>
        <value>返します<see cref="T:System.Int64" />別のキュー、トピック、またはサブスクリプションに転送されるメッセージの数を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>