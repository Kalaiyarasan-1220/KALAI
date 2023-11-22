import React, { useEffect, useState } from 'react';

const ErrorBoundary = ({ children }) => {
  const [hasError, setHasError] = useState(false);

  useEffect(() => {
    const handleError = (error, errorInfo) => {
      console.error('Error:', error, errorInfo);
      setHasError(true);
    };
  });

  if (hasError) {
    return <div>Something went wrong.</div>;
  }

  return <>{children}</>;
};

const MyComponent = () => {
  const numberList = [1, 2, 3, 4, 5];

  return (
    <ErrorBoundary>
      <div>
        <h1>Number List</h1>
        <ul>
          {numberList.map((number) => (
            <li key={number}>{number}</li>
          ))}
        </ul>
      </div>
    </ErrorBoundary>
  );
};

export default MyComponent;
