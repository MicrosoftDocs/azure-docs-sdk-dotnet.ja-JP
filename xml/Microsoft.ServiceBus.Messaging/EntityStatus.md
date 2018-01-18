<Type Name="EntityStatus" FullName="Microsoft.ServiceBus.Messaging.EntityStatus">
  <TypeSignature Language="C#" Value="public enum EntityStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntityStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EntityStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum EntityStatus" />
  <TypeSignature Language="F#" Value="type EntityStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="EntityStatus", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="98c17-101">メッセージング エンティティの状態の値を列挙します。</span><span class="sxs-lookup"><span data-stu-id="98c17-101">Enumerates the possible values for the status of a messaging entity.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-102">メッセージング エンティティの状態はアクティブです。</span><span class="sxs-lookup"><span data-stu-id="98c17-102">The status of the messaging entity is active.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Creating = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 5" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-103">リソースがまだ作成されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="98c17-103">Indicates that the resource is still being created.</span></span> <span data-ttu-id="98c17-104">作成しようとすると、同じリソース パスになります、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" />例外 (HttpCode.Conflict 409)。</span><span class="sxs-lookup"><span data-stu-id="98c17-104">Any creation attempt on the same resource path will result in a <see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" /> exception (HttpCode.Conflict 409).</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Deleting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 6" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-105">システムが、エンティティのクリーンアップを試みている最中ことを示します。</span><span class="sxs-lookup"><span data-stu-id="98c17-105">Indicates that the system is still attempting cleanup of the entity.</span></span> <span data-ttu-id="98c17-106">任意の追加的な削除の呼び出しが許可されます (システムが通知されます)。</span><span class="sxs-lookup"><span data-stu-id="98c17-106">Any additional deletion call will be allowed (the system will be notified).</span></span> <span data-ttu-id="98c17-107">同じリソース パスに、追加の作成の呼び出しの結果として、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" />例外 (HttpCode.Conflict 409)。</span><span class="sxs-lookup"><span data-stu-id="98c17-107">Any additional creation call on the same resource path will result in a <see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" /> exception (HttpCode.Conflict 409).</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Disabled = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 1" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-108">メッセージング エンティティの状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="98c17-108">The status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDisabled">
      <MemberSignature Language="C#" Value="ReceiveDisabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus ReceiveDisabled = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.ReceiveDisabled" />
      <MemberSignature Language="VB.NET" Value="ReceiveDisabled" />
      <MemberSignature Language="F#" Value="ReceiveDisabled = 4" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.ReceiveDisabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-109">メッセージング エンティティの受信側の状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="98c17-109">The receiving status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Renaming">
      <MemberSignature Language="C#" Value="Renaming" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Renaming = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Renaming" />
      <MemberSignature Language="VB.NET" Value="Renaming" />
      <MemberSignature Language="F#" Value="Renaming = 7" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Renaming" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-110">メッセージング エンティティの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="98c17-110">The messaging entity is being renamed.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Restoring">
      <MemberSignature Language="C#" Value="Restoring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Restoring = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Restoring" />
      <MemberSignature Language="VB.NET" Value="Restoring" />
      <MemberSignature Language="F#" Value="Restoring = 2" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Restoring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-111">メッセージング エンティティの以前の状態を再開しています。</span><span class="sxs-lookup"><span data-stu-id="98c17-111">Resuming the previous status of the messaging entity.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="SendDisabled">
      <MemberSignature Language="C#" Value="SendDisabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus SendDisabled = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.SendDisabled" />
      <MemberSignature Language="VB.NET" Value="SendDisabled" />
      <MemberSignature Language="F#" Value="SendDisabled = 3" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.SendDisabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-112">メッセージング エンティティの送信元の状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="98c17-112">The sending status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.EntityStatus Unknown = int32(99)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EntityStatus.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 99" Usage="Microsoft.ServiceBus.Messaging.EntityStatus.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>99</MemberValue>
      <Docs>
        <summary><span data-ttu-id="98c17-113">メッセージング エンティティの状態は不明です。</span><span class="sxs-lookup"><span data-stu-id="98c17-113">The status of the messaging entity is unknown.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>