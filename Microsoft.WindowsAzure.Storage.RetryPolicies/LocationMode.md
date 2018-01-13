<Type Name="LocationMode" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode">
  <TypeSignature Language="C#" Value="public enum LocationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LocationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum LocationMode" />
  <TypeSignature Language="F#" Value="type LocationMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            要求の受信場所を示す配置モードを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PrimaryOnly">
      <MemberSignature Language="C#" Value="PrimaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryOnly = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberSignature Language="VB.NET" Value="PrimaryOnly" />
      <MemberSignature Language="F#" Value="PrimaryOnly = 0" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            要求は、プライマリの場所に常に送信されます。
            </summary>
        <remarks>
            この値は、第 2 の場所 (たとえば GetServiceStats) に対してのみ機能する要求の使用は、クライアントの要求は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryThenSecondary">
      <MemberSignature Language="C#" Value="PrimaryThenSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryThenSecondary = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberSignature Language="VB.NET" Value="PrimaryThenSecondary" />
      <MemberSignature Language="F#" Value="PrimaryThenSecondary = 1" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            常に、プライマリの場所には要求は最初に送信されます。 失敗した場合、要求はセカンダリの場所に送信されます。
            </summary>
        <remarks>
            この値を 1 つの場所に対して有効な要求を使用する場合、クライアントはのみ許可されている場所をターゲットにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryOnly">
      <MemberSignature Language="C#" Value="SecondaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberSignature Language="VB.NET" Value="SecondaryOnly" />
      <MemberSignature Language="F#" Value="SecondaryOnly = 2" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            要求は、2 次拠点へ常に送信されます。
            </summary>
        <remarks>
            プライマリの場所に対してのみ機能するための要求に、この値を使用するかどうか (作成、変更、および Api を削除)、クライアントで、要求は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryThenPrimary">
      <MemberSignature Language="C#" Value="SecondaryThenPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryThenPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberSignature Language="VB.NET" Value="SecondaryThenPrimary" />
      <MemberSignature Language="F#" Value="SecondaryThenPrimary = 3" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            常に、2 次拠点には要求は最初に送信されます。 要求が失敗した場合、プライマリの場所に送信されます。
            </summary>
        <remarks>
            この値を 1 つの場所に対して有効な要求を使用する場合、クライアントはのみ許可されている場所をターゲットにします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>