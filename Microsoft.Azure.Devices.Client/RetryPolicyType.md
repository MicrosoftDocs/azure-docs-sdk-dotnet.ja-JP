<Type Name="RetryPolicyType" FullName="Microsoft.Azure.Devices.Client.RetryPolicyType">
  <TypeSignature Language="C#" Value="public enum RetryPolicyType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RetryPolicyType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.RetryPolicyType" />
  <TypeSignature Language="VB.NET" Value="Public Enum RetryPolicyType" />
  <TypeSignature Language="F#" Value="type RetryPolicyType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This enum has been deprecated.  Please use Microsoft.Azure.Devices.Client.SetRetryPolicy(IRetryPolicy retryPolicy) instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            DeviceClient でサポートされる方法の種類を再試行してください。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Exponential_Backoff_With_Jitter">
      <MemberSignature Language="C#" Value="Exponential_Backoff_With_Jitter" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.RetryPolicyType Exponential_Backoff_With_Jitter = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.RetryPolicyType.Exponential_Backoff_With_Jitter" />
      <MemberSignature Language="VB.NET" Value="Exponential_Backoff_With_Jitter" />
      <MemberSignature Language="F#" Value="Exponential_Backoff_With_Jitter = 1" Usage="Microsoft.Azure.Devices.Client.RetryPolicyType.Exponential_Backoff_With_Jitter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.RetryPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            指数関数的には強化し、再試行間隔と再試行の間隔で遅延をランダムな値を追加する再試行戦略。
            これは、既定のポリシーを使用するには
            </summary>
      </Docs>
    </Member>
    <Member MemberName="No_Retry">
      <MemberSignature Language="C#" Value="No_Retry" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.RetryPolicyType No_Retry = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.RetryPolicyType.No_Retry" />
      <MemberSignature Language="VB.NET" Value="No_Retry" />
      <MemberSignature Language="F#" Value="No_Retry = 0" Usage="Microsoft.Azure.Devices.Client.RetryPolicyType.No_Retry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.RetryPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            再試行なしです。  操作の 1 回の試行します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>