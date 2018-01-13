<Type Name="DeliveryAcknowledgement" FullName="Microsoft.Azure.Devices.DeliveryAcknowledgement">
  <TypeSignature Language="C#" Value="public enum DeliveryAcknowledgement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DeliveryAcknowledgement extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.DeliveryAcknowledgement" />
  <TypeSignature Language="VB.NET" Value="Public Enum DeliveryAcknowledgement" />
  <TypeSignature Language="F#" Value="type DeliveryAcknowledgement = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            メッセージ配信用の別の受信確認レベルを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement Full = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 3" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            配信の成功または失敗時に、受信確認が送信されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NegativeOnly">
      <MemberSignature Language="C#" Value="NegativeOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement NegativeOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.NegativeOnly" />
      <MemberSignature Language="VB.NET" Value="NegativeOnly" />
      <MemberSignature Language="F#" Value="NegativeOnly = 1" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.NegativeOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            配信が失敗した場合にのみ、受信確認が送信されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            受信確認は、配信またはエラーでは送信されません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PositiveOnly">
      <MemberSignature Language="C#" Value="PositiveOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement PositiveOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.PositiveOnly" />
      <MemberSignature Language="VB.NET" Value="PositiveOnly" />
      <MemberSignature Language="F#" Value="PositiveOnly = 2" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.PositiveOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            のみの配信が成功すると、受信確認が送信されます。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>