<Type Name="ActorCallType" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType">
  <TypeSignature Language="C#" Value="public enum ActorCallType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ActorCallType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ActorCallType" />
  <TypeSignature Language="F#" Value="type ActorCallType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="3eeb2-101">アクター ランタイムによって呼び出されるメソッドに関連付けられている呼び出しの種類を表します。</span><span class="sxs-lookup"><span data-stu-id="3eeb2-101">Represents the call-type associated with the method invoked by actor runtime.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="3eeb2-102">これは、一部として提供<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />への引数として渡される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />と<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />です。</span><span class="sxs-lookup"><span data-stu-id="3eeb2-102">This is provided as part of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> which is passed as argument to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> and <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorInterfaceMethod">
      <MemberSignature Language="C#" Value="ActorInterfaceMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType ActorInterfaceMethod = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ActorInterfaceMethod" />
      <MemberSignature Language="VB.NET" Value="ActorInterfaceMethod" />
      <MemberSignature Language="F#" Value="ActorInterfaceMethod = 0" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ActorInterfaceMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3eeb2-103">呼び出されたメソッドが特定のクライアント要求のアクター インターフェイス メソッドであることを指定します。</span><span class="sxs-lookup"><span data-stu-id="3eeb2-103">Specifies that the method invoked is an actor interface method for a given client request.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ReminderMethod">
      <MemberSignature Language="C#" Value="ReminderMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType ReminderMethod = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ReminderMethod" />
      <MemberSignature Language="VB.NET" Value="ReminderMethod" />
      <MemberSignature Language="F#" Value="ReminderMethod = 2" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ReminderMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3eeb2-104">メソッドが呼び出されることを示す<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />アラームが発生したときのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="3eeb2-104">Specifies that the method invoked on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface when a reminder fires.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TimerMethod">
      <MemberSignature Language="C#" Value="TimerMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType TimerMethod = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.TimerMethod" />
      <MemberSignature Language="VB.NET" Value="TimerMethod" />
      <MemberSignature Language="F#" Value="TimerMethod = 1" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.TimerMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3eeb2-105">タイマー コールバック メソッドに呼び出されるメソッドを指定します。</span><span class="sxs-lookup"><span data-stu-id="3eeb2-105">Specifies that the method invoked is a timer callback method.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>